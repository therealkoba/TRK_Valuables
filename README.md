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
| Item               | Durability | Value        | Phys Attribute | Phys Audio             | Volume Type |
|--------------------|------------|--------------|----------------|------------------------|-------------|
| AO_Figurine        | Weak++     | Medium++     | Light          | Ceramic Small          | Medium      |
| AO_Statue          | Strong+    | Expensive    | Heavy          | Metal Hollow Big       | Very Tall   |
| ShortSword         | Strong     | High         | Medium+        | Metal Hollow Medium    | Big         |
| BigCartoonSword    | Strong     | High         | Medium+        | Metal Hollow Medium    | Big         |
| TallCartoonSword   | Strong     | High         | Medium++       | Metal Hollow Medium    | Tall        |
| MediumAsteroid     | Strong     | Medium+      | Medium+++      | Rock Medium            | Medium      |
| SmallAsteroid      | Strong     | Medium       | Medium++       | Rock Medium            | Small       |
| TinyAsteroid       | Strong     | Very Cheap   | Medium         | Rock Medium            | Tiny        |

---

## Change Log

### v0.1.1 (Valuables Fix)
- Fixed the collider for the Short Sword so the top of the blade will no longer clip through the cart, floor, etc.
- Fixed the collider for the TallCartoonSword so it properly covers the Blade Grip.
- Decreased the size of the collider of each asteroid. They were made too big in v0.1.0.
- Adjusted the following Valuable Presets (not all were changed):

| Item               | Durability | Value        | Phys Attribute | Phys Audio             | Volume Type |
|--------------------|------------|--------------|----------------|------------------------|-------------|
| AO_Figurine        | Weak++     | Medium++     | Light          | Ceramic Small          | Medium      |
| AO_Statue          | Strong+    | Expensive    | Heavy          | Metal Hollow Big       | Very Tall   |
| ShortSword         | Strong     | High         | Medium+        | Metal Hollow Medium    | Big         |
| BigCartoonSword    | Strong     | High         | Medium+        | Metal Hollow Medium    | Big         |
| TallCartoonSword   | Strong     | High         | Medium++       | Metal Hollow Medium    | Tall        |
| MediumAsteroid     | Strong     | Medium+      | Medium+++      | Rock Medium            | Medium      |
| SmallAsteroid      | Strong     | Medium       | Medium++       | Rock Medium            | Small       |
| TinyAsteroid       | Strong     | Very Cheap   | Medium         | Rock Medium            | Tiny        |

### v0.1.0 (Feature Update)
- Update the REPOLib dependency from Zehs-REPOLib-2.1.0 to Zehs-REPOLib-3.0.2
- Added Cartoon Swords (One Big and One Tall — size variations of one model)
- Increased the size of the collider for each asteroid.
- Adjusted all Valuable Presets (Updating my project environment to v0.3.1 wiped all my existing presets. My fault probably.):

| Item               | Durability | Value        | Phys Attribute | Phys Audio             | Volume Type |
|--------------------|------------|--------------|----------------|------------------------|-------------|
| AO_Figurine        | Weak++     | Medium++     | Light          | Ceramic Small          | Medium      |
| AO_Statue          | Strong+    | Expensive++  | Very Heavy     | Metal Hollow Big       | Very Tall   |
| ShortSword         | Strong     | High         | Medium+++      | Metal Hollow Medium    | Big         |
| BigCartoonSword    | Strong     | High+        | Medium+++      | Metal Hollow Medium    | Big         |
| TallCartoonSword   | Strong+    | High+        | Medium++++     | Metal Hollow Medium    | Tall        |
| MediumAsteroid     | Strong     | Medium+      | Heavy          | Rock Medium            | Medium      |
| SmallAsteroid      | Strong     | Medium       | Medium++++     | Rock Medium            | Small       |
| TinyAsteroid       | Strong     | Very Cheap   | Medium+++      | Rock Medium            | Tiny        |


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
