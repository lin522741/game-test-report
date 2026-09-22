# Game Test Report
> Repository purpose: Store game test records, screenshots and bug logs

## Basic Info
- Game Name: Wangzherongyao
- Test Version: v1.1.0
- Test Date: 2026-09-22
- Tester: lin522741

## Game UI Screenshots
![Main Game UI](./screenshot/main_ui.jpg)

## Test Cases
| Case ID | Test Item | Expected Result | Actual Result | Status |
| ---- | ---- | ---- | ---- | ---- |
| TC001 | Launch game login | Enter main interface normally | Enter main interface normally | Pass |
| TC002 | Click mall button | Mall popup shows up | Blank popup | Bug |

## Bug List
1. Mall page shows blank, reproduction rate 100%
   - Screenshot: ![Mall Bug Screenshot](./screenshot/bug_shop.png)
   - Priority: High
2. Sound effect stutters when character moves
   - Priority: Medium

## Summary
2 bugs found in this test cycle, including 1 high-priority bug. Recommend fixing before next test phase.
