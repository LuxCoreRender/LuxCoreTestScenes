Author: Spiros Stavropoulos (xlxs)

Author's notes:
This blend file demonstrates how to setup a prism (https://en.wikipedia.org/wiki/Prism) and a laser using luxcore blender plug-in so that the rainbow colors can be rendered.
In the scene there is also an optional cylindrical lens (https://en.wikipedia.org/wiki/Cylindrical_lens) which serves the purpose of uncompressing the rays that pass through it on the Z direction (the more distance the rays travel, the more uncompressed they will be on the Z direction), so in the rendered image, the rainbow colors can be rendered with a typical camera and fill up all the space.If the optional lens didn't exist, the rainbow colors would be rendered as a thin line.

How to render with luxcoreui:
* Open luxcoreui application (get from https://luxcorerender.org/download/)
* Open the menu "Rendering -> Load" on the upper left
* Navigate into this folder and open "LuxCoreScene"
* Select the file "render.cfg" and click "Open"

How to render with Blender:
* You need to have the BlendLuxCore addon installed (https://github.com/LuxCoreRender/BlendLuxCore)
* Open the .blend file and press F12