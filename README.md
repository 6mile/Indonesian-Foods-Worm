# IndonesianFoods NPM Worm

## Overview
This is a coordinated NPM worm campaign involving multiple user accounts publishing malicious packages. The worm is contained in a single JavaScript file in each package.  The name of the file with the payload depends on the user.

## Identified NPM Users

| NPM User | Number of Packages | Payload File |
|----------|-------------------|--------------|
| veyla | 11942 | auto.js |
| doaortu | 496 | doaortu-payload.js |
| jarwok | 1821 | jarwok-payload.js |
| noirdnv | 12072 | noirdnv-payload.js |
| vndra | 11870 | vndra-payload.js |
| voinza | 13146 | voinza-payload.js |
| yunina | 12850 | yunina-payload.js |

## Total Impact
- **Total Users**: 7
- **Total Packages**: 64197 (minimum identified)

## Characteristics
- Naming scheme follows Indonesian food-related terminology
- Coordinated publication pattern across multiple accounts
- Internal dictionary uses bizarre Indonesian food references
- Each package contains a JavaScript payload file named after the user

## Status
Investigation ongoing. Additional users and packages may be identified.
