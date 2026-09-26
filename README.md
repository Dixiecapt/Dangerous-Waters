# Dangerous Waters - Beta (0.1.0)

Pirates for Sailwind. Guns you buy, carry, nail and fire; a pirate who sizes
you up, chases you, fires back, boards you and takes her cut; damage, splinters,
and a captain's manual to go with it.

The manual (DW_Manual.pdf, in this zip) is the full guide. This page is the
short version.

## Requirements

- Sailwind
- BepInEx 5 (installed by Thunderstore Mod Manager / r2modman)
- The **Old Chronian** ship mod. The pirate is built from its Caelanor. Without
  it there is no pirate.
- Recommended: **Configuration Manager** (press F1 in game for the settings).

## Install

Unzip into `BepInEx\plugins\`. You should get:

    BepInEx\plugins\DangerousWaters\DangerousWaters.dll
    BepInEx\plugins\DangerousWaters\dwpirates
    BepInEx\plugins\DangerousWaters\dwpirates.manifest
    BepInEx\plugins\DangerousWaters\Sounds\
    ... and a few text files beside them.

The folder must be named `DangerousWaters`. Start the game once. The settings
file `BepInEx\config\com.roy.dangerouswaters.cfg` is written on the first run.
Press F1 for the settings: about forty of them. Tick "Advanced settings" at
the top of F1 only if you want the two hundred tuning and diagnostic keys too.

**A save that has DW guns or shot aboard depends on this mod.** Uninstall it
and those items are gone from the save. This is true of any Sailwind mod that
adds items or ships: if a save stops loading after you remove a mod, put the
mod back, take its items off your ship, then remove it again, or use Save
Cleaner where the mod supports it.

Also in this zip: `DW_Manual.pdf`, the play-tester checklist (Word and
Markdown), `Snap DW Log.bat` (copies the game's log for a bug report) and the
three region maps.

## Where to start

Buy guns, powder and shot from the Cannon Merchant at Gold Rock City, Dragon
Cliffs, Fort Aestrin or Fort Chronos. Then sail out past the patrol reach of the
nearest port. The manual's charts (chapter IV) show where the dangerous waters
begin.

## The keys

| Key | What it does |
|---|---|
| Alt+F, looking at a gun | Pick her up / set her down |
| E or Right-click, on a gun | Aim mode (same keys leave it) |
| Left-click, in aim mode | Fire. On an empty swivel: order her loaded |
| W S / A D, in aim mode | Elevate / train |
| Keg or ball in hand, click on a gun | Load by hand: powder first, then the ball |
| Ctrl+Alt+K | Serve the guns: the crew loads every carriage gun from the stores |
| Ctrl+Alt+J / L | Fire the larboard / starboard battery |
| Alt+S, looking at a carronade | Stow her on her pin / run her out |
| Ctrl+Alt+Y | Nerve scan your own ship (writes to the log) |
| Ctrl+Alt+P | **Beta testers:** call a pirate now |
| F1 | Settings (Configuration Manager) |

A sealed crate of shot is cargo. Break it open aboard and the crew can serve
from it.

## Reporting bugs (please!)

Send `BepInEx\LogOutput.log` from the session, with what ship you were in,
where you were, and what the pirate was doing. The log is long and detailed on
purpose for this beta; the answer is nearly always in it.

Discord: the Sailwind modding channels. Ko-fi: ko-fi.com/dixiecapt

## Credits

By Dixiecapt. Pirate hull: Old Chronian's Caelanor, with permission. Port lid
mechanism after Le Requin 1750, with permission. Code guidance: LilithMotherOfAll.
Swivel gun after "Naval 0.75 swivel gun" by lvpublic (Cults, CC0). Gun reports
include BBC Sound Effects recordings (sound-effects.bbcrewind.co.uk, (c) BBC).
Ship ambience: HMS Rose recordings, King Collection: Watercraft Sound Effects
Library. Full credits in the manual, chapter XII.

Dangerous Waters (c) 2026 Dixiecapt. Free to download and play. Seek
permission to alter. You may share the link; you may not repackage, sell, or
re-upload the mod or its assets. Third-party assets remain under their own
licenses.
