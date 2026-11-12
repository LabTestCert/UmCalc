# UmCalc

This project is intended to create a tool for handling uncertainty budgets for calibration laboratories according to the GUM. The core feature is to evaluate the uncertainty of a measurement to the GUM. This core feature is used to help us calculate our Calibration Measurement Capabilities (CMCs) and the uncertainties of specific calibrations.

# Repo Structure

| Path                     | Description                                                                                           |
| ------------------------ | ----------------------------------------------------------------------------------------------------- |
| ./README.md              | This file - the basic top-level information about this repo.                                          |
| ./ActiveTasks/           | The boss. The Kanban. Tells us what we're working on, what's left to-do, and what's already done.     |
| ./ActiveTasks/Kanban.md  | The master file that tells us what work is active and what comes next.                                |
| ./ActiveTasks/Journal.md | The chronological history of things done recently.                                                    |
| ./CLAUDE.md              | The repo's AI context initializer. Claude will read this file before processing the first prompt.     |
| ./src/                   | Source code goes here.                                                                                |
| ./bin/                   | Compiled executables go here.                                                                         |
| ./data/                  | Data models, database schemas, migration scripts, and all documentation on data models and their use. |

# Architecture

Recommend making an architecture directory or at least an Architecture.md that gets called out here after briefly describing things from a high level.

# Active Tasks / Development Status

Development status in this repo is tracked using a Kanban board in `./ActiveTasks/Kanban.md`.

