# Server Commands

This page contains a comprehensive list of all commands available on the WyvenCraft server.

## 📋 Table of Contents
- [Basic Commands](#basic-commands)
- [Economy Commands](#economy-commands)
- [Social Commands](#social-commands)
- [Teleportation Commands](#teleportation-commands)
- [Home Commands](#home-commands)
- [Protection Commands](#protection-commands)
- [Shop Commands](#shop-commands)
- [Staff Commands](#staff-commands)

## Basic Commands

### Information Commands
| Command | Description | Usage |
|---------|-------------|-------|
| `/help` | Display help menu | `/help [page]` |
| `/rules` | View server rules | `/rules` |
| `/info` | Server information | `/info` |
| `/list` | Show online players | `/list` |
| `/ping` | Check your connection | `/ping` |
| `/playtime` | Check your playtime | `/playtime [player]` |
| `/stats` | View your statistics | `/stats [player]` |

### Player Commands
| Command | Description | Usage |
|---------|-------------|-------|
| `/spawn` | Teleport to spawn | `/spawn` |
| `/suicide` | Respawn at spawn | `/suicide` |
| `/afk` | Mark yourself as AFK | `/afk` |
| `/back` | Return to previous location | `/back` |

## Economy Commands

### Balance & Currency
| Command | Description | Usage |
|---------|-------------|-------|
| `/balance` | Check your balance | `/balance [player]` |
| `/bal` | Alias for balance | `/bal [player]` |
| `/pay` | Send money to another player | `/pay <player> <amount>` |
| `/baltop` | View richest players | `/baltop [page]` |

### Trading
| Command | Description | Usage |
|---------|-------------|-------|
| `/trade` | Request trade with player | `/trade <player>` |
| `/trade accept` | Accept trade request | `/trade accept` |
| `/trade deny` | Deny trade request | `/trade deny` |

## Social Commands

### Messaging
| Command | Description | Usage |
|---------|-------------|-------|
| `/msg` | Send private message | `/msg <player> <message>` |
| `/reply` | Reply to last message | `/reply <message>` |
| `/r` | Alias for reply | `/r <message>` |
| `/mail` | Access mail system | `/mail [send/read/clear]` |

### Friends & Parties
| Command | Description | Usage |
|---------|-------------|-------|
| `/friend` | Manage friends list | `/friend <add/remove/list>` |
| `/party` | Create or join a party | `/party <create/invite/leave>` |
| `/party chat` | Toggle party chat | `/party chat` |

## Teleportation Commands

### Teleport Requests
| Command | Description | Usage |
|---------|-------------|-------|
| `/tpa` | Request to teleport to player | `/tpa <player>` |
| `/tpahere` | Request player teleport to you | `/tpahere <player>` |
| `/tpaccept` | Accept teleport request | `/tpaccept` |
| `/tpdeny` | Deny teleport request | `/tpdeny` |
| `/tptoggle` | Toggle teleport requests | `/tptoggle` |

### Warps
| Command | Description | Usage |
|---------|-------------|-------|
| `/warp` | Teleport to a warp | `/warp <name>` |
| `/warps` | List all available warps | `/warps` |
| `/setwarp` | Create a warp (Staff) | `/setwarp <name>` |
| `/delwarp` | Delete a warp (Staff) | `/delwarp <name>` |

## Home Commands

### Home Management
| Command | Description | Usage |
|---------|-------------|-------|
| `/sethome` | Set a home location | `/sethome [name]` |
| `/home` | Teleport to home | `/home [name]` |
| `/homes` | List your homes | `/homes` |
| `/delhome` | Delete a home | `/delhome <name>` |
| `/homemax` | Check max homes allowed | `/homemax` |

## Protection Commands

### Claim Management
| Command | Description | Usage |
|---------|-------------|-------|
| `/claim` | Create a land claim | `/claim` |
| `/abandonclaim` | Delete a claim | `/abandonclaim` |
| `/abandonallclaims` | Delete all your claims | `/abandonallclaims` |
| `/trust` | Trust a player in claim | `/trust <player>` |
| `/untrust` | Remove trust from player | `/untrust <player>` |
| `/accesstrust` | Give access permission | `/accesstrust <player>` |
| `/containertrust` | Give container permission | `/containertrust <player>` |
| `/trustlist` | List trusted players | `/trustlist` |
| `/claimlist` | List your claims | `/claimlist` |
| `/subdivideclaims` | Create subclaim | `/subdivideclaims` |

### Locks
| Command | Description | Usage |
|---------|-------------|-------|
| `/lock` | Lock a container | `/lock` |
| `/unlock` | Unlock a container | `/unlock` |
| `/lwc` | LWC protection menu | `/lwc` |

## Shop Commands

### Player Shops
| Command | Description | Usage |
|---------|-------------|-------|
| `/shop` | Open shop menu | `/shop` |
| `/shop create` | Create a shop | `/shop create <price>` |
| `/shop remove` | Remove a shop | `/shop remove` |
| `/shop buy` | Buy from shop | Right-click shop sign |
| `/shop sell` | Sell to shop | Left-click shop sign |

### Auction House
| Command | Description | Usage |
|---------|-------------|-------|
| `/ah` | Open auction house | `/ah` |
| `/ah sell` | List item for sale | `/ah sell <price>` |
| `/ah search` | Search auctions | `/ah search <item>` |
| `/ah cancel` | Cancel your listing | `/ah cancel` |

## Staff Commands

*Note: These commands are only available to staff members*

### Moderation
| Command | Description | Permission Level |
|---------|-------------|------------------|
| `/kick` | Kick a player | Moderator |
| `/ban` | Ban a player | Moderator |
| `/unban` | Unban a player | Moderator |
| `/mute` | Mute a player | Moderator |
| `/unmute` | Unmute a player | Moderator |
| `/warn` | Warn a player | Moderator |

### Administration
| Command | Description | Permission Level |
|---------|-------------|------------------|
| `/tp` | Teleport to player/location | Admin |
| `/fly` | Toggle flight mode | Admin |
| `/gamemode` | Change game mode | Admin |
| `/give` | Give items | Admin |
| `/time` | Change world time | Admin |
| `/weather` | Change weather | Admin |

## Command Aliases

Many commands have shorter aliases for convenience:
- `/msg` = `/m`, `/tell`, `/w`
- `/balance` = `/bal`, `/money`
- `/teleport` = `/tp`
- `/tpaccept` = `/tpyes`
- `/tpdeny` = `/tpno`

## Command Cooldowns

Some commands have cooldowns to prevent spam:
- **Teleport requests:** 30 seconds
- **Home teleport:** 10 seconds
- **Spawn teleport:** 5 seconds
- **Back command:** 15 seconds

## Tips

💡 **Pro Tips:**
- Use Tab to auto-complete player names
- Most commands support partial name matching
- Use `/help <command>` for detailed help on specific commands
- Teleport commands have a warmup period - don't move!

## Need Help?

If you need assistance with any command:
1. Try `/help <command>` in-game
2. Ask in chat or contact a staff member
3. Join our [Discord](https://discord.gg/wyvencraft)
4. Check the [Features](Features.md) page for gameplay features

---

**Last Updated:** November 2025 | See something missing? [Report it!](https://github.com/WyvenCraft/official-server/issues)
