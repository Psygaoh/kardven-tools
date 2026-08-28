# Riftbound Tracker Glossary

This glossary defines the core terms used by the Riftbound game-tracking application. It intentionally stays focused on concepts needed for the MVP.

## Core terms

| Term | Definition |
|---|---|
| **User** | A registered account in the application. |
| **Player** | A person participating in a Riftbound game. Usually a User; guest players may be supported later. |
| **Playgroup** | A persistent group of players who regularly play together. A Game may be associated with a Playgroup, but this is optional. |
| **Game** | One individual game of Riftbound, from start until a winner or final result is determined. |
| **Match** | A competitive encounter that may contain several Games. Reserved for later competitive/tournament support and should not be used as a synonym for Game. |
| **Game Mode** | The configuration used for a Game. See the supported modes below. |
| **Team** | A group of Players competing together in a team-based Game Mode. |
| **Points** | The score tracked during a Game. Prefer this term over generic terms such as life, health or score when referring to the Riftbound victory total. |
| **Winner** | The Player or Team that won a completed Game. |
| **Result** | The stored final outcome of a completed Game. |
| **Deck** | Optional information identifying what a Player used in a Game. For the MVP, the deck can primarily be identified by its Legend rather than by a full decklist. |
| **Game History** | The collection of completed Games associated with a User, Player or Playgroup. |
| **Statistics / Stats** | Aggregated information derived from recorded Games and Results. |

## Game modes

The initial supported Game Modes are:

| Internal name | UI label | Description |
|---|---|---|
| `1V1` | **1v1** | Two players competing against each other. |
| `2V2` | **2v2** | Four players competing as two teams of two. |
| `3playerFFA` | **3-player FFA** | Three players competing in a free-for-all. |
| `4playerFFA` | **4-player FFA** | Four players competing in a free-for-all. |

## Product conventions

- Anyone can create and start a Game; Playgroup membership or organizer approval is not required.
- A Game may optionally be linked to a Playgroup.
- The application is player-centric rather than association-centric. An association such as Kardventure is simply one possible Playgroup.
- `Game` and `Match` must remain distinct terms.
- Detailed card-system vocabulary such as Rune, Domain, Unit, Spell or Gear is intentionally outside the MVP glossary.
