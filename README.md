# Pool Club Management System

A Windows Forms desktop app (C#) that manages up to 9 pool tables at the same time. Each table runs its own session timer and calculates the fee when the session ends.

## Features
- 9 independent tables, each with a player name and a live session timer
- Stop and End buttons per table
- On End, the app shows the time consumed, total seconds, hourly rate, and total fee
- Fee is calculated from the hourly rate and the time played
- Each table is a reusable custom `UserControl` (`ctrlPoolTable`)

## Tech Stack
- C#, Windows Forms, .NET Framework 4.7.2
- Visual Studio

## What I Learned
- Building reusable custom controls
- Running several timers independently
- Separating UI code from calculation logic
