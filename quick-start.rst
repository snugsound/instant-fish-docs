###########
Quick Start
###########

To get started, simply drag and drop a fish prefab into your scene. Upon playing, the fish will swim around the scene, avoiding any colliders.

You can find the fish prefabs in:
``Cosmocat\InstantFish\Prefabs``

.. IMPORTANT::
   If you modify a prefab be sure to save it as a new prefab (or prefab variant) outside of the Cosmocat directory.

By default, the water level is 0 on the Y-axis. The fish will not swim above this level. If you would like to override this, add a ``WaterLevel`` component to your scene and adjust as needed. 