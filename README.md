# IndonesianFoods NPM Worm

## Overview
This is a coordinated NPM worm campaign involving multiple user accounts publishing malicious packages. The worm is contained in a single JavaScript file in each package.  The name of the file with the payload depends on the user.

## Identified NPM Users

| NPM User | Number of Packages | Payload File |
|----------|-------------------|--------------|
| veyla | 5250 | auto.js |
| doaortu | 496 | auto.js |
| jarwok | 1821 | publishScript.js |
| noirdnv | 5250 | auto.js |
| vndra | 5250 | publishScript.js |
| voinza | 5250 | auto.js |
| yunina | 5250 | auto.js |
| sernaam.b.y | 4468 | ? |
| rudiox | 435 | ? |
| bipyruss | 5250 | ? |

## Total Impact
- **Total Users**: 10
- **Total Packages**: 38720 (minimum identified)

## Characteristics
- Naming scheme follows Indonesian food-related terminology
- Coordinated publication pattern across multiple accounts
- Internal dictionary uses bizarre Indonesian food references
- Each package contains a JavaScript payload file named after the user

## Status
Investigation ongoing. Additional users and packages may be identified.
