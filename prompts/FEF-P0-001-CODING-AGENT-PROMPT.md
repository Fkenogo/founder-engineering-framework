# TASK — FEF-P0-001: Repository Baseline and Programme Initiation

## ROLE

Act as the coding agent responsible for establishing the safe initial repository baseline for the Founder Engineering Framework.

You are not authorized to define or approve the Framework Constitution, final authority hierarchy, mandatory project obligations, or FEF v1.0.

## REPOSITORY

Local repository:

`~/founder-engineering-framework`

Confirm the expanded absolute path before making changes.

## CONTEXT

The repository has been newly created and cloned into an empty folder.

FEF is intended to become a reusable, governed framework adopted by Founder-led projects including 11thONUS, Kirimba, XamPreps, TrafoLog, CareNest, Klockit, and future projects.

FEF must be treated as its own governed project. It must also avoid prematurely claiming authority over existing projects.

## OBJECTIVE

Create a clean, minimal, documentation-first repository baseline that:

1. records the initial repository state;
2. establishes a controlled documentation structure;
3. records programme initiation and roadmap;
4. establishes draft/non-authoritative status notices;
5. prepares the repository for methodology inventory and constitutional development;
6. leaves the worktree validated and, only if explicitly authorized, committed.

## FIRST ACTION — INSPECT, DO NOT ASSUME

```bash
cd ~/founder-engineering-framework
pwd
git status --short --branch
git branch --show-current
git rev-parse --is-inside-work-tree
git rev-parse HEAD 2>/dev/null || true
git remote -v
find . -maxdepth 3 -type f -not -path './.git/*' | sort
```

If the repository is not empty, inventory all existing content before modification. Do not delete, overwrite, or reorganize unexpected files.

## REQUIRED REPOSITORY STRUCTURE

```text
founder-engineering-framework/
├── README.md
├── docs/
│   ├── constitution/
│   ├── governance/
│   ├── programme/
│   ├── product-methodology/
│   ├── engineering/
│   ├── ai-collaboration/
│   ├── knowledge-preservation/
│   ├── reviews-and-audits/
│   ├── adoption/
│   ├── templates/
│   └── records/
├── prompts/
└── .gitignore
```

Use `.gitkeep` only where required to preserve an empty directory.

## REQUIRED DOCUMENTS

Create:

1. `README.md`
2. `docs/programme/FEF-PROGRAMME-INITIATION.md`
3. `docs/programme/FEF-INITIAL-ROADMAP.md`
4. `docs/programme/FEF-DOCUMENT-MANIFEST.md`
5. `docs/governance/FEF-DRAFT-PRINCIPLES.md`
6. `docs/records/FEF-WORK-PACKAGE-REGISTER.md`
7. `docs/records/FEF-DECISION-REGISTER.md`
8. `docs/records/FEF-SOURCE-METHODOLOGY-REGISTER.md`
9. `docs/records/FEF-CHANGELOG.md`

## CONTENT BOUNDARIES

Use the framework status:

`Draft — Not Yet Adoptable`

Do not state that any project has adopted FEF. Do not state that FEF supersedes project-specific constitutions or standards. Do not invent approval dates or Founder approvals. Do not assign final authority levels unless clearly marked as proposals.

## INITIAL REGISTERS

The work-package register must include FEF-P0-001 through FEF-P1-004.

The decision register must contain open placeholders for framework scope, constitutional authority, FEF/project relationship, authority model, mandatory/optional modules, releases, adoption, deviations, legacy standards, and minimum v1.0 criteria.

The source register must identify 11thONUS, Kirimba, XamPreps, TrafoLog, CareNest, Klockit, and prior WORKING_WITH_KENOGO materials. Mark review and provenance pending unless source files are actually present.

## VALIDATION

```bash
git status --short
find . -maxdepth 4 -type f -not -path './.git/*' | sort
grep -RniE "FEF v1\\.0.*(Approved|Active|Adopted)|Status:.*Active|Founder Approved" README.md docs prompts || true
grep -RniE "11thONUS|Kirimba|XamPreps|TrafoLog|CareNest|Klockit" README.md docs prompts
```

Manually confirm that no adoption, approval, or supersession has been invented and that all navigation and registers are consistent.

## COMMIT BOUNDARY

Do not commit unless explicitly authorized in the coding-agent session.

If authorized, use:

`chore(fef): establish programme foundation`

Before committing, report the exact files to be committed.

## FINAL REPORT

Return:

1. repository path;
2. branch;
3. starting HEAD or unborn-branch status;
4. initial repository contents;
5. files created and modified;
6. validation commands and results;
7. unresolved decisions;
8. worktree status;
9. commit hash only if committed;
10. recommended next task.

The recommended next task should normally be:

`FEF-P0-002 — Source Methodology Inventory and Provenance Register`.
