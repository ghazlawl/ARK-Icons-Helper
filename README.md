# ARK-Icons-Helper
A blueprint library used to create icons for structures.

## How-to

Will update this later. Long story short, do this:

1. Pre-place structures in the viewport. (Place near a wall for best results.)
2. Create `IconsHelper` object on `Event Begin Play` in the level blueprint.
3. Add delay.
4. Call function on `IconsHelper` object to set the floor material to green (or black).
5. Add delay.
6. Call function on `IconsHelper` object to move the player to a structure.
7. Look at the structure and take a screenshot.
8. Repeat Steps 5-7 until done.
