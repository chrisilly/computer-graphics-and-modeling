Chris Culling

Lab report for **Mod-L3**

17 Dec 2024

---

I started by making a cube with one material/texture per side as per the instructions:

> Bake diffuse textures for two models in two separate scenes:
>
> 1. **A simple object,** such as a cube.
> 2. A **more complex** object from L1 or L2, such as the Trojan airplane.
>
> The source objects should have at least a handful of different materials and textures. One per face when it comes to a cube, for example.

I suffered for way too long because Maya has this button that toggles the viewing of textures and I did not realise why my textures were not showing this program sucks please replace it with Blender

![alt text](screenshots/source-and-destination-cubes.png)

When I tried to bake, it didn't work despite copying the settings in the demo on canvas. I suspect it may have to do with having applied materials and textures to the *faces* instead of the UV-shells.

Correction: It did not automatically apply the generated PNG as a texture onto the destination cube. I noticed also that two of the sides did not come out right in the PNG, presumably because they made use of shaders that don't translate into PNG format.

Manually setting the destination cube's texture to the newly generated cubeDiffuse.png worked perfectly fine otherwise.

