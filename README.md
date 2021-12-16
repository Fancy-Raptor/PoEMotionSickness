# PoE Motion Sickness Reshade preset

## Shaders included:
Reshade contributors are the best. Big shoutout to Fu-Bama for the VR.fx shader in particular which makes this possible.  
Monocular_Cues (Depth_Cues.fx) - BlueSkyKnight  
Flashlight (Flashlight.fx)- luluco250  
DELC_Sharpen (qUINT_sharp.fx) - martymcmodding  
Virtual Reality (VR.fx) - Fu-Bama  
bulgepinch (bulgepinch.fx - RadegastFFXIV  
UIMask_Bottom/Top (UIMask.fx)  
Overlay (Overlay.fx)  
UIMask_Top (UImask.fx)  

Install Reshade first then dump the contents of this zip in your PoE game folder. The default overlay hotkey for Reshade is the 'home' key. Once the menu is open click the right arrow next to the preset selector or path to this preset.

Recommended shader order: [*] Required placement

UIMask_Top *  
Monocular_Cues  
Flashlight  
DELC_Sharpen  
Bulge/Pinch  
Virtual Reality  
UIMask_Bottom *  
Overlay  

## Things to know / troubleshooting: 

- Why is my border not aligned?   
In the option for the overlay you can mess with the scale settings. My monitor is 1080p and lines up perfectly with scale set to 1.5

- Can I turn off or change the border?  
You can but there's going to be a lot of empty black space. I don't play with the border on myself; I added it to make this all less confusing. If you want to help even up the space you can set the game to windowed mode, make your desktop background pure black, then use Windowed Borderless Gaming to move the window up by -30 or so on the Y axis. It works out to kind of look like you're watching a janked movie. If you want to make a new border, 'overlay.fx' shader looks for "Layer.png" in reshade's textures folder. You can edit that or specify a different file.

- Why is my mouse cursor misaligned at the edges of the screen?  
The lens distortion messes with the whole screen. (e.g that's why the border exists) I recommend you make a macro which hits the key you set to disable reshade (home by default), waits 50ms or so, then hits your keys to open inventory as well as the character sheet. Having everything open at once like the Torchlight games gets rid of this issue entirely.

- Can I get rid of that weird shimmering by the health and mana globes?  
Clicking off the 'UIMask' shaders will remove the edge shimmer and show the ui how it would otherwise. Like I said, the lens distortion skews everything.

- Why the bulgepinch, sharpening, and flashlight shaders?  
Some common issues for people who suffer from motion sickness in games are lack of physical grounding for the character model and not enough emphasis. The spotlight and pinch at the feet are slight but help me out. The sharpening is more personal taste but it absolutely helps the visual clarity.

Anyway, yeah, that's about all. Hopefully this helps somebody else! - Rap
