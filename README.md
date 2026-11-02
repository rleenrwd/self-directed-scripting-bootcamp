# Personal Scripting Bootcamp

**Status: In Progress — curriculum planned; implementation begins with Project 1.**

A self-directed bootcamp consisting of **10 practical scripting projects using Python and PowerShell**, followed by a standalone portfolio capstone.

I created this learning initiative outside my degree coursework to strengthen my ability to automate repetitive tasks, troubleshoot systems, process data, and build useful tools for software development and IT operations.

## Goals

- Build confidence writing scripts from requirements.
- Practice automation tasks relevant to software development and IT.
- Develop reliable scripts with input validation, error handling, and clear output.
- Use parameters, configuration files, and documentation to make tools reusable.
- Apply the skills from these exercises to a complete portfolio capstone.

## Projects

Each project will live in its own numbered folder with source code, usage instructions, relevant sample data, and verification steps or tests appropriate to its scope.

### Python

| # | Project | Scope | Status |
|---|---|---|---|
| 01 | **Folder Inventory** | Scan a folder and report filenames, extensions, sizes, and totals. Export results to CSV. | Planned |
| 02 | **File Organizer** | Organize files by type, preview proposed changes, and handle duplicate filenames. | Planned |
| 03 | **CSV Quality Checker** | Detect missing fields, duplicate IDs, and invalid values. Export an issues report. | Planned |
| 04 | **API Health Checker** | Check configured endpoints and report status codes, response times, and failures. | Planned |
| 05 | **Log Analyzer** | Parse sample application logs, summarize errors, and filter results by date or severity. | Planned |

### PowerShell

| # | Project | Scope | Status |
|---|---|---|---|
| 06 | **Computer Inventory Report** | Collect Windows version, CPU, RAM, and disk information. Export a structured report. | Planned |
| 07 | **Service Health Monitor** | Check selected Windows services, flag unexpected states, and save timestamped results. | Planned |
| 08 | **New-Hire Workspace Builder** | Create folder structures and setup checklists from fictional employee data, with `-WhatIf` support. | Planned |
| 09 | **File Backup and Verification** | Copy a practice folder and verify file integrity using hashes. Report missing or mismatched files. | Planned |
| 10 | **Workstation Readiness Checker** | Check required applications, selected services, and free disk space against configurable requirements. | Planned |

## Capstone: Workstation Readiness & Diagnostics Toolkit

**Status: Planned · Languages: PowerShell + Python · Repository: Separate, link forthcoming**

The capstone will combine the skills developed throughout the bootcamp to answer:

> Are these Windows workstations ready for employees, and what needs attention?

Planned components include:

- **PowerShell collector:** Gather computer information and run readiness checks.
- **JSON configuration:** Define required applications, services, and minimum free disk space.
- **Structured reports:** Save timestamped results for each computer in a consistent JSON format.
- **Python report generator:** Combine computer reports into an HTML dashboard showing readiness and issues.
- **Synthetic demonstration data:** Show multiple workstation scenarios using reports that can be demonstrated from one machine.
- **Documentation:** Include setup instructions, example commands, screenshots, and known limitations.

The capstone will have its own repository so it can be presented and used independently.

## Learning Approach

Projects will be completed one at a time, with increasing complexity:

1. Define the task, inputs, and expected results.
2. Break the problem into manageable steps.
3. Build a small working version.
4. Verify normal behavior and relevant failure cases.
5. Add improvements that serve the task.
6. Document usage, decisions, and lessons learned.

The emphasis is on understanding the code and making deliberate decisions about reliability, safety, and usability.

## Running the Projects

Usage instructions and prerequisites will be added to each project’s README as implementation progresses. Python exercises will run against local practice data or explicitly configured endpoints. PowerShell exercises will target Windows, with version requirements documented per project.

## Practice Data and Environment

Exercises will use practice folders, synthetic records, sample logs, and authorized systems or endpoints. Scripts that modify files will include previews or other safeguards appropriate to the task.

---

**This repository is actively being developed. Project statuses and documentation will be updated as work progresses.**