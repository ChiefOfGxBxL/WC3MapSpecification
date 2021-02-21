# WC3MapSpecification
The specification of WC3 .w3x files as a living document

## File versions
| WarCraft III | Terrain               | Units†                  | Doodads†                  | Regions             | Cameras             | Sounds             | Objects             | Strings††           | Info               | Imports             |
|--------------|:---------------------:|:-----------------------:|:-------------------------:|:-------------------:|:-------------------:|:------------------:|:-------------------:|:-------------------:|:------------------:|:-------------------:|
| 1.32.9.16589 | [11](./Terrain/11.md) | [8_11](./Units/8_11.md) | [8_11](./Doodads/8_11.md) | [5](./Regions/5.md) | [0](./Cameras/0.md) | [3](./Sounds/3.md) | [2](./Objects/2.md) | [1](./Strings/1.md) | [31](./Info/31.md) | [1](./Imports/1.md) |
| Pre-reforged | [11](./Terrain/11.md) | [8_11](./Units/8_11.md) | [8_11](./Doodads/8_11.md) | [5](./Regions/5.md) | [0](./Cameras/0.md) | [1](./Sounds/1.md) | [2](./Objects/2.md) | [1](./Strings/1.md) | [25](./Info/25.md) | [1](./Imports/1.md) |

† Units and Doodads files seem to have a version and subversion. Or it's possible the "11" integer is not part of the version and has just never changed or is unused by WC3.  
†† Strings file does not have a version number; we have assigned v1

## Files
 * Terrain (`war3map.w3e`)
 * Units (`war3mapUnits.doo`)
 * Doodads (`war3map.doo`)
 * Regions (`war3map.w3r`)
 * Cameras (`war3map.w3c`)
 * Sounds (`war3map.w3s`)
 * Objects (`war3map.w3u` `war3map.w3t` `war3map.w3a` `war3map.w3b` `war3map.w3d` `war3map.w3q` `war3map.w3h`)
 * Strings (`war3map.wts`)
 * Info (`war3map.w3i`)
 * Imports (`war3map.imp`)

## Types
 * `byte`
 * `short`
 * `int`
 * `float`
 * `char(X)`
 * `string`
 * `unknown(X)`