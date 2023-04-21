# WC3MapSpecification
The specification of WC3 .w3x files as a living document

## File versions

| WarCraft III      | 1.32.9.16589                  | Pre-reforged                  |
|-------------------|-------------------------------|-------------------------------|
|      Terrain      |     [11](./Terrain/11.md)     |     [11](./Terrain/11.md)     |
|       Units†      |    [8_11](./Units/8_11.md)    |    [8_11](./Units/8_11.md)    |
|      Doodads†     |   [8_11](./Doodads/8_11.md)   |   [8_11](./Doodads/8_11.md)   |
|      Regions      |      [5](./Regions/5.md)      |      [5](./Regions/5.md)      |
|      Cameras      |      [0](./Cameras/0.md)      |      [0](./Cameras/0.md)      |
|       Sounds      |       [3](./Sounds/3.md)      |       [1](./Sounds/1.md)      |
|      Objects      |      [2](./Objects/2.md)      |      [2](./Objects/2.md)      |
|     Strings††     |      [1](./Strings/1.md)      |      [1](./Strings/1.md)      |
|        Info       |       [31](./Info/0-31.md)    |      [25](./Info/0-31.md)     |
|      Imports      |      [1](./Imports/1.md)      |      [1](./Imports/1.md)      |
| GameConfiguration | [1](./GameConfiguration/1.md) | [1](./GameConfiguration/1.md) |

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
 * GameConfiguration (`.wgc`)

## Types
 * `byte`
 * `short` - 2 bytes, Little-Endian
 * `int` - 4 bytes, Little-Endian (usually unsigned)
 * `float` - IEEE 32-bit floating point, Little-Endian
 * `char(X)` - 1-byte ASCII character repeated X times
 * `string` - a stream of characters, usually UTF-8, zero-terminated
 * `unknown(X)` - treat as X bytes of binary data
