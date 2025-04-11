![header.png](https://raw.githubusercontent.com/CharleRoger/ChemicalStorage/main/header.png)

# Chemical Storage
A set of highly configurable tanks for storing single chemicals. This mod can be thought of as an extension of CryoTanks and is intended to be paired with other mods which make use of the supported chemicals.

## Features
Chemical Technologies considers two types of liquid resource:
- **Storable** (at ambient temperature, including condensed gases under pressure): LqdAmmonia, LqdCO2, Kerosene, Hydrazine, NTO, Water.
- **Cryogenic** (configured with CryoTanks boiloff): LqdCO, LqdHydrogen, LqdMethane, LqdNitrogen, LqdOxygen.

This mod provides three types of tank which store different chemicals in different ways:
- **Basic**: Plain old tanks, stores stock chemicals if Chemical Propulsion is not installed and storable chemicals depending which other mods are installed.
- **Heavy-duty Cryogenic**: Stores cryogenic chemicals in heavy tanks with very low boiloff rates and cheap boiloff prevention, intended for storing chemicals long-term on orbit or the ground.
- **Lightweight Cryogenic**: Stores cryogenic chemicals in mass-optimised lightweight tanks, equivalent to those provided by CryoTanks.

### Parts
Each tank has a fixed diameter with several configurable lengths and model and texture variants. So far, only 2.5m and 3.75m cylindrical tanks have been added, with spherical tanks and 5m, 7.5m and 10m sizes at various stages of development:
- "CT-2B 2.5m Basic Chemical Tank"
- "CT-2H 2.5m Heavy-duty Chemical Tank"
- "CT-2L 2.5m Lightweight Chemical Tank"
- "CT-3B 3.75m Basic Chemical Tank"
- "CT-3H 3.75m Heavy-duty Chemical Tank"
- "CT-3L 3.75m Lightweight Chemical Tank"
- "CT-4B 5m Basic Chemical Tank"
- "CT-4H 5m Heavy-duty Chemical Tank"
- "CT-4L 5m Lightweight Chemical Tank"

### Planned
- 7.5m and 10m tanks
- Spherical tanks at double diameters
- More intelligent CryoTanks integration which should make the separate tank types unnecessary
- More interesting textures

## Dependencies
### Required
- [ModuleManager (4.2.3)](https://github.com/sarbian/ModuleManager)
- [B9PartSwitch (2.20.0)](https://github.com/blowfishpro/B9PartSwitch)
- [Chemical Core (0.5.0)](https://github.com/CharleRoger/ChemicalCore)
- [CryoTanks (1.6.6)](https://github.com/post-kerbin-mining-corporation/CryoTanks)
### Supported
- [VABOrganizer 1.0.1](https://github.com/post-kerbin-mining-corporation/VABOrganizer)

## Compatibility
Backwards compatibility is not guaranteed for any v0.x, use at your own risk. If you find any other mod to be incompatible with this one, please let me know via a github issue.

## License
The art assets in this mod are distributed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

Everything else is distributed under the GNU General Public License.
