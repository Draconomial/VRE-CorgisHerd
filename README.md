# VRE Corgis Herd Too

A compatibility mod for **RimWorld 1.7** that lets more dogs learn **Herd** in [Vanilla Ranching Expanded](https://github.com/Vanilla-Expanded/VanillaRanchingExpanded).

It makes selected breeds eligible for Herd training; it doesn't train them automatically.

## Requirements

- RimWorld 1.7
- Vanilla Ranching Expanded (and its dependencies)
- Any of the animal mods below, if you want their dogs to herd. They're all optional.

## Supported dogs

The mod patches 23 animal definitions across 12 mods. Different mods sometimes add the same breed.

| Animal mod | Dogs |
| --- | --- |
| Vanilla Animals Expanded | Corgi, German Shepherd, Rottweiler, Poodle |
| Stray Dogs | Border Collie, Collie, Old English Sheepdog, Welsh Corgi, Swedish Vallhund, Standard Poodle, Bernese Mountain Dog, Schnauzer |
| Erin's Fluffy Fauna | Corgi |
| Border Collies | Border Collie |
| German Shepherd | German Shepherd |
| Malinois | Belgian Malinois |
| Sheepdog | Border Collie |
| Swedish Vallhund | Swedish Vallhund |
| Rimshepherd | Rimshepherd |
| Grimstone Beasts | Sheepdog |
| Vanilla Genetics Expanded | Dogman, Mechawolf |
| HC Animal | Samoyed |

Vanilla Ranching Expanded's own Collie already supports Herd and doesn't need a patch.

## Installation

1. Download this repository as a ZIP and extract it into your RimWorld `Mods` folder. The extracted mod folder should contain `About` and `Patches`.
2. Enable **Vanilla Ranching Expanded** and **VRE Corgis Herd Too** in your mod list.
3. Load this mod after Vanilla Ranching Expanded and the animal mods you're using.

## Notes

I chose dogs based on their herding history or potential, rather than simply including every canine. Dogman and Mechawolf are deliberate fictional exceptions; I included Mechawolf because a mechanical canine could plausibly be programmed to herd livestock.

The XML patches add the `VRE_Herd` eligibility tag only when the animal exists and doesn't already have it. Normal training requirements still apply. Some targeted breeds may be unavailable in current versions of their source mods; not every combination has been tested in-game.

For exact `ThingDef` names and inclusion decisions, see [BREED_DECISIONS.csv](BREED_DECISIONS.csv).
