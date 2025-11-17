# TRK Valuables

**TRK Valuables** is a custom R.E.P.O. mod that introduces unique valuables based on 3D models I personally created in Blender and Blockbench.

---

## Features

### Valuables
- **Statue**
- **Figurine**
- **Asteroids**
  - Medium Asteroid
  - Small Asteroid
  - Tiny Asteroid
- **Short Sword**
- **Cartoon Sword**
  - Big Cartoon Sword
  - Tall Cartoon Sword

### Valuables' Presets
- AO_Figurine
  | Durability: Weak++
  | Value: Medium++
  | Phys Attribute: Light 
  | Phys Audio: Ceramic Small
  | Volume Type: Medium
- AO_Statue
  | Durability: Strong+
  | Value: Expensive++
  | Phys Attribute: Very Heavy
  | Phys Audio: Metal Hollow Big
  | Volume Type:
- ShortSword
  | Durability: Strong
  | Value: High
  | Phys Attribute: Medium+++
  | Phys Audio: Metal Hollow Medium
  | Volume Type: Big
- BigCartoonSword
  | Durability: Strong
  | Value: High+
  | Phys Attribute: Medium+++
  | Phys Audio: Metal Hollow Medium
  | Volume Type: Big
- TallCartoonSword
  | Durability: Strong
  | Value: High+
  | Phys Attribute: Medium++++
  | Phys Audio: Metal Hollow Medium
  | Volume Type: Tall
- MediumAsteroid
  | Durability: Strong
  | Value: Medium+
  | Phys Attribute: Heavy
  | Phys Audio: Rock Medium
  | Volume Type: Medium
- SmallAsteroid
  | Durability: Strong
  | Value: Medium
  | Phys Attribute: Medium++++
  | Phys Audio: Rock Medium
  | Volume Type: Tiny
- TinyAsteroid
  | Durability: Strong
  | Value: Very Cheap
  | Phys Attribute: Medium+++
  | Phys Audio: Rock Medium
  | Volume Type: Tiny
---

## Change Log

### v0.1.0 (Feature Update)
- Update the REPOLib dependency from Zehs-REPOLib-2.1.0 to Zehs-REPOLib-3.0.2
- Added Cartoon Swords (One Big and One Tall — size variations of one model)
- Adjusted all Valuable Presets (Updating my project environment to v0.3.1 wiped all my existing presets. My fault probably.):
  - AO_Figurine
    | Durability: Weak++
    | Value: Medium++
    | Phys Attribute: Light
    | Phys Audio: Ceramic Small
    | Volume Type: Medium
  - AO_Statue
    | Durability: Strong+
    | Value: Expensive++
    | Phys Attribute: Very Heavy
    | Phys Audio: Metal Hollow Big
    | Volume Type: Very Tall
  - ShortSword
    | Durability: Strong
    | Value: High
    | Phys Attribute: Medium+++
    | Phys Audio: Metal Hollow Medium
    | Volume Type: Big
  - BigCartoonSword
    | Durability: Strong
    | Value: High+
    | Phys Attribute: Medium+++
    | Phys Audio: Metal Hollow Medium
    | Volume Type: Big
  - TallCartoonSword
    | Durability: Strong
    | Value: High+
    | Phys Attribute: Medium++++
    | Phys Audio: Metal Hollow Medium
    | Volume Type: Tall
  - MediumAsteroid
    | Durability: Strong
    | Value: Medium+
    | Phys Attribute: Heavy
    | Phys Audio: Rock Medium
    | Volume Type: Medium
   SmallAsteroid
    | Durability: Strong
    | Value: Medium
    | Phys Attribute: Medium++++
    | Phys Audio: Rock Medium
    | Volume Type: Small
  - TinyAsteroid
    | Durability: Strong
    | Value: Very Cheap
    | Phys Attribute: Medium+++
    | Phys Audio: Rock Medium
    | Volume Type: Tiny

### v0.0.1 (Version Re-alignment)
- Changed version to align with Semantic Versioning
  - https://semver.org/

### v0.0.0.1 (Bugfix Release)
- **Removed Big Asteroid**: Item was oversized and unable to pass through standard doors.  
- **Renamed Trophy to Figurine**: Fixed naming conflict with existing valuables.  

### v0.0.0 (Initial Release)
- Added Statue valuable (large)  
- Added Trophy (smaller figurine of the Statue model)  
- Added Asteroid set (Big, Medium, Small, Tiny — size variations of one model)  
- Added Short Sword valuable  

---

## Known Issues

### v0.0.0
- **Big Asteroid was oversized**: Could not fit through standard doors.
- **Naming conflict**: Valuable named *"Valuable Trophy"* caused the error:  
  `Failed to register valuable "Valuable Trophy". Valuable prefab already exists in Resources with the same name.`

---
