
# Lab_Task_8
# VV-Lab-<RollNo>-PSVS: Polar Seed Vault System (Verification & Validation Lab)

**Name:** <RIDA FATIMA>  **Roll No:** <sp-2024-BSSE-069>

## Overview
This repository contains V&V work for the Polar Seed Vault System (PSVS). The vault stores sealed seed boxes deposited by registered institutions. It is a custodian, not an owner.

## Folder Structure
| Folder | Purpose |
|---|---|
| /requirements | Baselined requirements S1-S12, change-request template |
| /defect-logs | Defect taxonomy, defect log, peer review |
| /abstractions | Abstract data types / state abstractions |
| /models | Formal models |
| /operations | Operation specifications (deposit, withdraw, ...) |
| /constraints | Invariants and constraints |
| /proofs | Proof obligations and proofs |
| /reports | Summary tables, charts, final reports |

## Configuration Management
- Baseline: `PSVS-REQ-v1.0` tagged as `baseline-1`
- Work on `defect-analysis` branch, merged into `main` with `--no-ff`
- Changes to baselined artifacts need a change request (`/requirements/change-request-template.md`)

## Tasks
- [x] Task 1: Orientation and configuration management
- [x] Task 2: Defect taxonomy and verification logging
