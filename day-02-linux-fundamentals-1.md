# Day 02 — Linux Fundamentals Part 1 (TryHackMe)

**Date:** 2026-09-20
**Status:** ✅ Completed (5 tasks, 64 pts)
**Type:** Foundational skills (not blue-team specific)

## Key Takeaways
- Linux is everywhere: web servers, cars, PoS systems, phones, IoT, critical infra
- Interaction with Linux happens through the **terminal** (command line), not a GUI
- A **command** is an instruction telling the computer to perform a task
- Arrow ↑ / ↓ keys scroll through previously entered commands

## Commands Learned
| Command | What it does |
|---|---|
| `whoami` | Tells you who you are on the system (current user) |
| `echo "text"` | Outputs text back to you |
| `ls` | Lists files/folders in the current directory |
| `cd` | Changes folder (directory) |
| `cat <file>` | Outputs contents of a file |
| `pwd` | Shows where you are in the filesystem |
| `find -name <file>` | Searches for files by name |
| `grep "text" <file>` | Searches *inside* a file for text |

## Shell Operators
| Operator | Meaning |
|---|---|
| `&` | Runs command in background (doesn't wait to finish) |
| `&&` | Runs both commands, waits for the first to finish first |
| `>` | Redirects output to a file, **overwrites** existing content |
| `>>` | Redirects output to a file, **appends** to the bottom |

## Screenshot
![Linux Fundamentals Pt1 complete](screenshots-day-02-linux-fundamentals-1.png)
