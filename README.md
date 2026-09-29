# Bistro-Blocks

Roblox game managed with [Rojo](https://rojo.space).

## Setup
1. Install Rojo (`aftman install`, or the Rojo VS Code extension) and the Rojo plugin in Studio.
2. Run `rojo serve` in this folder.
3. In Studio, open the Rojo plugin and click Connect.

## Layout
| Folder | Syncs to |
| --- | --- |
| `src/server` | `ServerScriptService.Server` |
| `src/client` | `StarterPlayer.StarterPlayerScripts.Client` |
| `src/shared` | `ReplicatedStorage.Shared` |
