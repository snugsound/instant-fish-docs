##########################
Performance & Optimization
##########################

Each fish prefab is comprised of the following:

* Two skinned mesh renderers
* A mesh renderer per additional body (jaw, fins, eyes, etc.)
* Two or more materials (body, fins, eyes, etc.)

Fish are approximately 2-3K triangles, depending on the number and type of fins.

Instant Tropical Fish performs the following optimizations automatically:

* Converting one skinned mesh renderer to a regular mesh renderer (the skinned mesh renderer is only needed for blend shapes, which aren't used at runtime)
* Combining meshes where possible

The following additional optimizations can be carried out by the user if needed:

* Turning off ``Cast Shadows``
* Turning off ``Receive Shadows``