# C Workbench

This is an ongoing workspace for me to practice about C/C++. It includes study 
notes, as well as programming exercises and practices.

I started this repository to rebuild my C fluency before the Imperial C
project and my robotics internship. I continue to use it for HackerRank and
LeetCode interview practices.

## How I study

I use QSCHA: questions, syntax hints, conceptual hints, and answers.

1. Attempt a question with the knowledge I already have.
2. Use syntax hints when I need help with language features or functions.
3. Use conceptual hints when I need help with the logic.
4. Compare my attempt with the answer, then repeat with fewer hints.

The notebooks retain my attempts and later corrections.

## Topics

- Pointers, structs, and memory allocation.
- Dynamic arrays and linked lists.
- Binary file input and data validation.
- Bit fields, sign extension, and instruction data.
- Regular expressions and finite-state machines.
- Makefiles, compiler warnings, and sanitizers.
- Telemetry data and system-design interview practice.

## Repository structure

```text
c-labs/
├── department-lists/    # Linked lists of people and departments
├── dynamic-array/       # Integer vector with unit tests
├── fread/               # Binary file input exercises
├── include-analysis/    # C include analysis with trees and sets
├── interview-drills/    # Bit operations and telemetry parsers
├── makefile-practice/   # Build-system exercises
└── regex-fsm/           # Regular-expression and state-machine labs
notebooks/              # Dated notes and practice
interview-prep/         # Question bank and system-design template
docs/                   # Toolchain notes and study context
```

## Start here

- [Dynamic array](c-labs/dynamic-array/) — Memory allocation and API tests.
- [Binary input](c-labs/fread/) — Read and validate binary records.
- [Interview drills](c-labs/interview-drills/) — Short C exercises.
- [Study notebooks](notebooks/) — Notes from each practice session.
- [Question bank](interview-prep/question-bank.md) — System-design prompts.

Selected notebook topics:

| Notebook | Focus |
| --- | --- |
| [May 17](notebooks/May-17.ipynb) | Pointers and memory allocation |
| [May 24](notebooks/May-24.ipynb) | Makefiles and instruction data |
| [May 25](notebooks/May-25.ipynb) | Binary input with `fread` |
| [June 6](notebooks/June-06.ipynb) | Pointers and file input |

## Run the dynamic-array tests

Use Clang and Make. From the repository root:

```bash
cd c-labs/dynamic-array
make CC=clang test
```

The default compiler flags enable AddressSanitizer and
UndefinedBehaviorSanitizer. Other exercises have separate build setups.

## Sources and licence

Some coursework labs include supplied scaffolding and test utilities.
Their local README files describe those materials.

The root [LICENSE](LICENSE) contains the MIT License.