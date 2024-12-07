# Metroid Off-Screen Visualization Script

This script visualizes off-screen areas and entities in NES *Metroid*. It is compatible with the FCEUX, BizHawk, and Mesen emulators.

All credit belongs to the original author, [@metalmachine76](https://github.com/metalmachine76).

## Features
- Displays off-screen sections of the game world
- Highlights various game entities such as Samus, enemies, and environment elements (solid and breakable tiles)

## Compatibility
- **Mesen**
- **FCEUX**
- **BizHawk**

## Usage
- Open your emulator (e.g., FCEUX, BizHawk, or Mesen)
- Load the Metroid ROM
- Open the Lua script window and load this script

## Visual Elements

| Element         | Color                | Description                          |
|------------------|----------------------|--------------------------------------|
| Samus            | White               | Highlights Samus' position.         |
| Enemies          | Yellow-green        | Highlights enemy positions.         |
| Solid tiles      | Light gray | Displays solid tiles. |
| Breakable tiles  | Red | Displays breakable tiles. |
| Edges            | Light cyan          | Shows boundaries of scrolling areas.|

## Changelog
- v3.2:  Add Mesen support
- v3.1:  Original script