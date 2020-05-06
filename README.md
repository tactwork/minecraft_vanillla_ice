# minecraft_vanillla_ice
[Download] SEUS PTGI E12























HOTFIX 1: Fixed a few dumb compile errors that only an idiot could miss. Re-download to get a version that solves the issue.



SEUS PTGI E12 is here! This version takes the clouds and sky introduced in E11 and improves upon them significantly. There's also improved (and adjustable) "water fog", and some fixes to the GI filter that caused issues with high resolution resource packs with normal maps.



Here's the changelog:

Improved cirrus and cumulus clouds! Coverage varies from almost no clouds to somewhat cloudy over long periods of time instead of constant coverage, and they now extend to the horizon
Improved sky, lighting, and cloud colors. Everything is now using the same physically based functions, so consistency and accuracy is improved. Outdoor scenes should look much more natural in many ways!
Added "horizon" to sky, instead of having just a white void below the horizon. It's supposed to give the impression of a distant ocean/landscape.
Improved land atmospheric scattering. Uses the new functions mentioned above.
Rain lighting reworked. Probably will be reworked again. Try out sunset or sunrise, nice warmly lit clouds creates dramatic scenes!
Adjusted rain fog
New physically-based water fog
Added new Options screen: Water
Added Water > Water Fog Density option
GI noise filter adjustments. Should be a little less artifacty than in E11. E11 and E12 use a much faster filter than before, and now I'm trying to improve the image quality of this new filter.
Fixed issue where the GI filter would cause some areas to over-darken, especially on resource packs with normal maps or custom leaf block models. I don't know how I didn't notice this before!
Fixed fences not contributing to GI or being rendered in ray traced reflections
Reduced sunlight shadow artifacts on surfaces where the sunlight is at a grazing angle to them
Multi-bounce GI is no longer allowed to let indoor areas made up of brightly colored blocks look super neon/glowy. 
Reduced the size of the sun as rendered directly in the sky
Made the sun look less like a lonely, dim, ugly white disc in the sky
Fixed GI light from clouds leaking all over the place inside caves
Fixed ray traced reflections appearing grayscale if they were too dark
Reflections on water now better approximate apparent reflectivity based on the presence of waves.
Fixed crazy circular random lighting artifacts when standing too close to a block
Fixed bug where GI from clouds wasn't being properly rendered when underwater, causing underwater areas to look too brightly lit
Improved SEUSTonemap tonemapping operator's handling of purely-colored bright highlights.
Removed ancient forgotten code in SEUSTonemap that caused unnatural colors
Fixed intense flickering on distant blocks


 

PLEASE READ THE FOLLOWING REQUIREMENTS FOR USING THIS SHADER PACK!


Minecraft 1.14.4 (older version compatibility is work in progress)
OptiFine HD U F3 or newer
Options > Video Settings > Details > Alternate Blocks: OFF
Options > Video Settings > Details > Trees: Fancy or Fast (Smart may break lighting)
Options > Video Settings > Quality > Natural Textures: OFF
Options > Video Settings > Shaders > Shadow Quality: 1x
Options > Video Settings > Shaders > Old Lighting : DEFAULT
Resource packs with custom block models will probably cause  lighting glitches!!!!!!
Some of the currently known issues are as follows:



Block texture alpha is not considered in diffuse GI tracing, so doors and trapdoors don't let any light through their windows currently.
Being underwater in ravines/caves shows light leaking, and “glowing” water fog. This is unavoidable currently.
"Disco Floor" flickering artifact mostly seen in reflections (the new Secondary GI Samples option can help with this)
Secondary GI bounces (2nd bounce and onward) can take a while to adapt to lighting changes
Issues with the rendering of semi-transparent/translucent materials
Lighting breaks often when using resource packs with custom models, a solution is being investigated!
AN IMPORTANT NOTE ON GRAPHICS DRIVER ISSUES AND GPU COMPATIBILITY:

Since different GPUs can compile shaders differently than others, you may experience compile errors (causes "[Shaders] Error: Invalid program..." messages to appear in the in-game chat). 

If you experience compile errors and you're using an NVIDIA GPU, you can help me fix them by following the steps on this page, in the "How to Report a Compile Error" drop-down section and sending me the log!

Compatibility with AMD GPUs is being actively worked on. You will still experience some minor visual bugs, and you may experience random crashing. If you experience crashing while trying to load the game or enable SEUS PTGI, try doing so first in windowed mode, with a small window.

Compatibility with Intel GPUs is not guaranteed or planned at all!
