##########################
Frequently Asked Questions
##########################

**Q: Can I use my own textures?**

Of course! 

* Import your texture(s)
* Create a new material and assign the texture(s)
* Create a new ``FishProfile`` and set the materials as desired. (Note that it may be easier to copy an existing profile, as this will retain the fin settings.)

**Q: Can I change the physical shape or structure of the fish?**

The structure of the fish can be altered in various ways:

* The head and body expose several blend shape keys which can be used to alter their appearance. 
* (Advanced) Those with knowledge of modelling tools can create custom fin meshes. Open ``fish_parts.fbx`` (the original .blend file is also included) to see how the anchors are set. Once modelled, create a new (or copy an existing) profile and assign your custom fins.
* (Advanced) Fins can be added, repositioned, or moved. Note that adding or removing fins will require updating references on the Fish component.

As always, when modifying any of the base prefabs be sure to create a new prefab (or prefab variant) outside of the Cosmocat directory.

**Q: Can I use my own AI?**

To use your own AI, uncheck the Move checkbox on the Fish component.

As always, when modifying any of the base prefabs be sure to create a new prefab (or prefab variant) outside of the Cosmocat directory.

**Q: Can I use my own animations?**

Due to the procedural nature of the fish, this is not recommended, but if you are interested in doing so please contact adam@cosmocatgames.com.




