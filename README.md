<p align="center">
  <img src="./docs/logo.png" alt="Size Limit CLI" width="720">
</p>

Skyrim SE tool for worldbuilding

The navmeshing/Dungeon tools seemed too useful to lump in with Undaunted so they've been split out here.


# Tools

# Player location based navmesh generation 

Tracks the players movement through a cell and places joined quads under their feet.

This can then be exported to a sse edit script which will create the navmesh on the targeted cell.

Once applied the navmeshes are standard nav meshes, with no dependency on mundusform.

This should help rough out a navmesh that can be refined if necessary.


# block based dungeon generation 

Similar to games like diablo and warframe, defining tiles in a json format and procedural generating a complete dungeon with working navmesh.
Built to support Undaunted rifts but built to be useful for quickly laying out dungeons for any author.

Output will be a sseedit script to add the cell to an esp so the output will be completely editable via standard tools.

# cell snapshot tool

Creating blocks by hand is time consuming, so instead the cell snapshot tool can capture all the references in the current cell.

With a few simple rules new blocks can be created rapidly.
The snapshot tool also works with the player navmesh tool, allowing quick layout of block navmeshes.
