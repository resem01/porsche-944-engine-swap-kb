# Research and Publication Workflow

The repository separates **discovery** from **accepted technical documentation**.

## 1. Discover

Sources enter through:
- manual research
- the web-monitoring task
- builder submissions
- project-owner files, CAD, photographs and measurements

New findings normally enter as GitHub Issues or research-inbox material.

## 2. Evaluate

Each finding is classified by evidence type and checked for:
- configuration
- source identity
- date
- measurement method
- contradiction with existing information
- whether later information supersedes it

## 3. Draft

Substantive documentation changes are made on a branch, not directly on `main`.

## 4. Review

A Pull Request shows the exact files and lines proposed for change. Review should ask:
- Is the claim supported?
- Is the evidence class correct?
- Is a vendor claim clearly attributed?
- Are contradictory measurements preserved?
- Is superseded information identified rather than erased?

## 5. Merge

After review, the Pull Request is merged into `main`.

**`main` is the currently accepted edition of the knowledge base.**

## 6. Correct

Corrections follow the same process. Git history preserves what changed and why.

Small typographical/formatting corrections may be committed directly when appropriate, but technical changes should
normally remain auditable through Pull Requests.
