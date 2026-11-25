# Windows Failed Login Investigation

**Status:** Planned  
**Level:** Beginner

## Objective
Find and interpret failed Windows sign-in events and consider whether activity is suspicious.

## Tools
Windows Event Viewer, Windows Security logs, PowerShell (optional)

## Lab Steps
1. Use a test machine and test account you control.
2. Generate a small number of controlled failed sign-in attempts.
3. Open Event Viewer and review Windows Security logs.
4. Record relevant event IDs, timestamps, account context, and source details when available.
5. Build a short timeline and identify what additional evidence is needed.

## Evidence to Add
Include the event details you observed, a short timeline, your interpretation, and a screenshot with sensitive details removed.

Suggested additions after completing the lab:
- `screenshots/` — screenshots captured from your own environment
- `notes.md` — observations and explanations
- `analysis.md` or `incident-report.md` — investigation summary, where appropriate

## Questions to Answer
- What were you trying to find out?
- What did you do, and why?
- What did you observe?
- What does the evidence support, and what does it not prove?
- What would you investigate next?

## Safety and Accuracy
A few failed attempts alone do not prove brute force. Only test systems and accounts you own or are authorized to use.

Do not mark this project Complete until you have performed the steps yourself, checked the results, and added your own evidence.

## Results
_To be completed after performing the lab. Do not invent results._
