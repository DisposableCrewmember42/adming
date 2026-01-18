# Basic Commands

> [!NOTE]
> For an overview of admin menus and verbs, check out the [upstream Admin Tooling docs](https://docs.spacestation14.com/en/community/admin/admin-tooling.html)

## De-/Activating Admin privileges
### readmin
|Syntax|Description|
|:-------|:-----------|
| ``readmin`` | Enable your admin privileges. |

### deadmin
|Syntax|Description|
|:-------|:-----------|
| ``deadmin`` | Disables your admin privileges to play like normal. |

### aghost
|Syntax|Description|
|:-------|:-----------|
| ``aghost`` | Turns you into a fancy ghost with an inventory that can interact with the live round. |


## Gathering information
### adminlogs
|Syntax|Description|
|:-------|:-----------|
| ``adminlogs`` | Opens the floating logs window.|

### adminoverlay
|Syntax|Description|
|:-------|:-----------|
| ``adminoverlay <bool>`` | Alternative to clicking the toggle overlay button in the F7 player menu. |

### listgamerules
|Syntax|Description|
|:-------|:-----------|
| ``listgamerules`` | This command will print a list of currently active game rules, allowing you to see previous spawns and the current game mode at a glance. |

- If the ``RampingStationEventScheduler`` is present, the game mode is Survival.
- If the ``BasicStationEventScheduler`` is present, you can identify the gamemode by antag-specific gamerules such as ``Nukeops`` or ``Traitors``.
- Some round-start antagonists don't roll immediately; the respective game rules will be shown as ``[PENDING]`` until the roles are filled.

### lsobjectives
|Syntax|Description|
|:-------|:-----------|
| ``lsobjectives <username>`` | Prints the antagonist objectives of the requested player to your console.|

### menuvis
|Syntax|Description|
|:-------|:-----------|
| ``menuvis [mode]`` | Allows you to make items inside of containers visible to you in the context menu.|

- Use ``menuvis ALL`` to view inside closed lockers and other containers by right-clicking.
    * Watch out, people are containers too and you can take out their organs as an aghost!
- Use ``menuvis`` without any arguments to go back to normal.

## Moderation
### adminnotes
|Syntax|Description|
|:-------|:-----------|
| ``adminnotes <username>`` | Opens the note menu on the specified user |

### ban_exemption_update
|Syntax|Description|
|:-------|:-----------|
| ``ban_exemption_update <username> <flag>`` | Exempt an account from specific kinds of bans. |
- Flag ``IP``: Used to exempt someone from a non-VPN IP Ban. Use this if they are affected by another player's ban.
- Flag ``Datacenter``: Used to exempt someone from VPN/Datacenter bans.

### rename
|Syntax|Description|
|:-------|:-----------|
| ``rename <username> <new character name>`` | Used to properly rename a player mid-round. |


## Miscellaneous
### toggleshadows
|Syntax|Description|
|:-------|:-----------|
| ``toggleshadows`` | Will toggle rendering of shadows client-side. Less straining on the eyes than fullbright while still allowing you to see clearly in most situations. |

#### 
