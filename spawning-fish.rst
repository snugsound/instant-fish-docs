#############
Spawning Fish
#############

Instant Tropical Fish comes bundled with a fish spawning component which will spawn fish on a 3D grid, avoiding any colliders in your scene. To make use of this component, add a new GameObject to your scene and assign the ``FishSpawner`` component. Adjust the following parameters as needed:

* **Fish:** Type of fish to spawn
* **Bounds:** Bounding box for fish spawning
* **Cast Shadows:** Should fish cast shadows?
* **Receive Shadows:** Should fish receive shadows?
* **Fish Density:** Percentage of bounds to fill with fish

.. TIP::
   The bounding box provides an editor to make adjustments.

.. IMPORTANT::
   This asset is not optimized for large quantities of fish. Spawning too many fish will degrade performance. Always be sure to profile your game relative to the target hardware.