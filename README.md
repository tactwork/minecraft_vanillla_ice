# minecraft_vanillla_ice

## 1. install version 1.xx.x of minecraft
## 2. install optifine 1.xx.x of optifine
  paste file in or copy to dir below
    C:\Program Files (x86)\Minecraft Launcher\runtime\jre-x64\bin
  open cmd
    cd C:\Program Files (x86)\Minecraft Launcher\runtime\jre-x64\bin
  then run 
    java.exe -jar optifine.jar
  
## 3. install shaderpack in %appdata%/.minecraft
## 4. install vanilla pbr resouirce pack.

## settings

Options > Video Settings > Details > Alternate Blocks: OFF
Options > Video Settings > Details > Trees: Fancy or Fast (Smart may break lighting)
Options > Video Settings > Quality > Natural Textures: OFF
Options > Video Settings > Shaders > Shadow Quality: 1x
Options > Video Settings > Shaders > Old Lighting : DEFAULT
Resource packs with custom block models will probably cause  lighting glitches!!!!!!

##Some of the currently known issues are as follows:

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
