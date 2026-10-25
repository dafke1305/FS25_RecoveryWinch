# Recovery Winch — User guide

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

For the **1.0.0.2** package linked in [this release](https://github.com/dafke1305/FS25_RecoveryWinch/releases/tag/v1.0.0.2). These instructions describe that ZIP, not another build sharing its version number.

## Installation

1. Download **FS25_RecoveryWinch.zip** from the release Assets. Keep that filename and do not extract it; the automatic GitHub Source code archives are not the mod.
2. Put the ZIP in FS25's configured mods folder (normally `Documents\My Games\FarmingSimulator2025\mods` on Windows) and enable it before loading the savegame. These script mods require PC/Mac.
3. On multiplayer/dedicated servers, the server and every client need the **identical ZIP**, not just the same version label. Close the game/stop the server and back up the save before updating.

## Buy suitable recovery equipment

- Configure a compatible car, pickup, truck, loading bed or forestry forwarder with a winch in the vehicle shop/workshop. Availability depends on the vehicle category, mount points and bed definitions.
- For a tractor, buy the separate **Category 2 three-point recovery winch** under **Weights**. It weighs 220 kg, requires no PTO and fits a compatible front or rear linkage. The linkage itself is not automatically a rope attachment point.
- A purchased winch costs 1,500 and includes 20 m cable and one reusable portable towing eye for the farm. Cable options run from 20 to 50 m in 5 m steps; extra cable costs 250 per metre.
- Mounted winches offer fore/aft and height adjustments where applicable. The separate three-point unit has a fixed mount.

## Recover a vehicle

1. Position a suitable winch vehicle on stable ground and align it with the pull. Use the recovery parking brake while stationary when needed.
2. On foot, use the contextual **pick up/release cable** action near the winch. Default: **Y**.
3. Walk the cable to a supported standing tree, eligible vehicle recovery point or available supported free drawbar coupling. Use the F1 attachment action for the highlighted target.
4. If a car/pickup/truck has no suitable point, fit the portable towing eye on foot with **Alt+E**. The target does not need its own winch purchase. Other farms' vehicles can also be recovered.
5. Use the native winding/unwinding controls shown by F1 or **Controls**. Release the connection through the contextual detach action after recovery.

## Controls

| Action | Default/context |
| --- | --- |
| Pick up / release cable | **Y**, on foot near the winch |
| Deploy / release ground anchor | **Ctrl+G**, while controlling an eligible winch vehicle |
| Recovery parking brake | **Ctrl+B**, eligible vehicle; stop first |
| Fit / remove portable towing eye | **Alt+E**, on foot near an eligible target |
| Eye height / depth while positioning | **Alt+Up/Down** / **Alt+Left/Right** |
| Confirm / cancel eye position | **Alt+C** / **Alt+Backspace** |
| Attach, detach, wind, unwind | Native contextual actions; follow F1/current bindings |

If anchor placement is refused, move to clear space and try an eligible position rather than repeatedly placing into an obstruction.

## Loading beds, limits and persistence

Lower supported ramps and start the target approximately aligned behind them. The rear-facing bed winch can provide steering/brake assistance to an unattended target, represented by a seated helper. That assistance **does not start its engine or apply throttle**; the winch supplies the pulling force. Secure the loaded vehicle using the carrier's appropriate equipment.

Grip, collisions, bed movement, dimensions and weight distribution still matter. In this release a small recovery car can slide toward a heavy target or lose front-axle loading; heavy loads are not protected by a mass-ratio refusal popup. Use equipment suited to the actual load.

Purchased equipment/shop configurations are saved. Cable connections, ground anchors and fitted towing eyes are temporary; reconnect after loading a save.

If an option/prompt is missing, check that a winch is actually purchased, the correct implement is selected, you are close enough and the target is supported. Custom scripts and moving/tilting beds may need compatibility work. Admin compatibility/debug switches are under **ESC > Game Settings**, require an in-game server administrator and do not guarantee every custom vehicle will work.

## Get help

Use [this mod's bug/support form](https://github.com/dafke1305/FS25_RecoveryWinch/issues/new/choose). Include the release/ZIP, FS25 and map versions, singleplayer/host/client/dedicated role, steps, incident time, full client `log.txt` and matching `server.log` for a dedicated-server incident. Add relevant screenshots/video. The package checksum is in [PUBLICATION.json](PUBLICATION.json). Remove passwords/tokens/private connection details before posting; send private evidence only through an approved private channel.

Keyboard defaults can be rebound. Current F1 prompts and your Controls settings take precedence.
