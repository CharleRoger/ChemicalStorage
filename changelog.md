# 0.4.1
- Fixed cryo tank foil material shininess
# 0.4.0
- Removed most resources from tanks, leaving the following default profiles:
  - Basic tanks: LiquidFuel, Oxidizer, MonoPropellant
  - Cryo tanks: LqdMethane, LqdHydrogen
# 0.3.0
- Added 5m configurable cylindrical chemical tanks:
  - "CT-4B 5m Basic Chemical Tank"
  - "CT-4H 5m Heavy-duty Cryogenic Chemical Tank"
  - "CT-4L 5m Lightweight Cryogenic Chemical Tank"
- Added VABOrganizer support
- Fixed 3.75m bulkhead profile sizes
- Adjusted the position and appearance of "Ground horizontal" base models on 3.75m tanks
# 0.2.0
- Renamed from "Immersive Chemical Storage" to "Chemical Storage"
- Consolidated texture variants into two B9 part switches, one controlling the "material" (normal texture) and another controlling the "paint" (colour texture), with unique material properties when unpainted
# 0.1.1
- Fixed missing topology on 2.5m dome long tube mesh
- Simplified truss models for 2.5m and 3.75m cryo tanks
- Removed patches messing with CryoTanks parts
- Reordered basic tank surface switches
- Minor texture improvements
# 0.1.0
- Pre-release
- Added 2.5m configurable cylindrical chemical tanks:
  - "CT-2B 2.5m Basic Chemical Tank"
  - "CT-2H 2.5m Heavy-duty Cryogenic Chemical Tank"
  - "CT-2L 2.5m Lightweight Cryogenic Chemical Tank"
- Added 3.75m configurable cylindrical chemical tanks:
  - "CT-3B 3.75m Basic Chemical Tank"
  - "CT-3H 3.75m Heavy-duty Cryogenic Chemical Tank"
  - "CT-3L 3.75m Lightweight Cryogenic Chemical Tank"
- Added length switch to tanks.
- Added model switch to tanks.
- Added surface switch to tanks.
- Added stock and storable tank types to basic chemical tank fuel switch:
  - LiquidFuel
  - Oxidizer
  - MonoPropellant
  - LqdAmmonia
  - LqdCO
  - Kerosene
  - Hydrazine
  - NTO
  - Pentaborane
  - Water
- Added cryogenic tank types to heavy-duty and lightweight cryogenic tank fuel switch:
  - LqdCO2
  - Diborane
  - LqdFluorine
  - LqdHydrogen
  - LqdMethane
  - LqdNitrogen
  - LqdOxygen
- Assigned tank types to native parts and CryoTanks parts.
- Patched CryoTanks spherical tank volumes to their realistic values.