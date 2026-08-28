# Kardven Tools — Riftbound Tracker

## Project goal

Kardven Tools aims to provide a simple companion application for playing and tracking **Riftbound** games.

The core idea is to let anyone quickly create a game with friends, track points during play, and automatically save the final result once the game ends.

The project takes inspiration from tools such as **Mythic Tools** for Magic: The Gathering, but is designed around Riftbound's own terminology, game modes, and scoring flow.

## Core principles

- **Anyone can create a game.** No association membership, organizer role, or approval is required.
- **Playgroups are optional.** Players may create persistent groups for friends, clubs, associations, or local communities, but a Game does not need to belong to one.
- **The application is player-centric.** Kardventure is one possible Playgroup, not the root structure of the application.
- **The live game experience comes first.** Starting a Game and tracking Points should be fast and comfortable on a phone at the table.
- **Results are recorded automatically.** Completed Games should feed player and Playgroup histories and statistics without requiring duplicate manual entry.
- **Riftbound terminology should be respected.** Product wording and data concepts should follow official Riftbound vocabulary where relevant.

## Initial scope

The first version should focus on a straightforward flow:

1. Select or add the Players.
2. Choose a supported Game Mode.
3. Optionally associate the Game with a Playgroup.
4. Start the Game.
5. Track Points during play.
6. End the Game and determine the Winner.
7. Save the Result automatically.
8. Make the Game available in Player and Playgroup history and statistics.

Initial Game Modes:

- **1v1**
- **2v2**
- **3-player FFA**
- **4-player FFA**

## Longer-term direction

The MVP should remain deliberately small, while leaving room for later features such as richer player statistics, Deck/Legend tracking, competitive Matches, tournament support, and broader community features.

The detailed vocabulary used by the project is documented in [`glossary.md`](./glossary.md).
