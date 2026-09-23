# Knowledge

## Dictionary

### Motion graphics
Umbrella term for any digital animation, 2D or 3D, where each frame is rendered using interpolated key frame values; the artist changes parameters like shape, color and position and the computer does the rest.
Usually used to describe animations for commercial use. Films like Disney's Snow White would be called *animation*. whereas the Netflix logo animation would be called *motion graphics*.

### Frame-by-frame animation
Umbrella term that can include many types of animation, as long as each frame is an independent artwork.

### Stop motion
Manual animation where each frame is captured by a camera. The actual media captured can differ, giving birth to many sub-genres of stop-motion:
Brickfilms (LEGO fan movies), clay-mation (Walter & Gromit, go-motion (Battle of Hoth, Star Wars), cut-outs (Terry Gilliam's Monty Python animations).

### Interpolation
A transition between two or more values over time. Interpolations are integral to keyframe animations.

### Feedback
A process in which the output of the process also acts as an input. Integral method to many video artworks and widely used across many tools, digital and analog.<br>
**Example of internal feedback:**
A video mixer outputs a signal that is fed back into one of the inputs being mixed. The delay and characteristics caused by the signal processing of the mixing device causes feedback artifacts.
**Example of external feedback:**
A video camera points at a monitor that shows what the camera is filming. The delay and characteristics of the camera and screen processing the image, and external factors like room lighting, position of the camera all effect the produced image.



# Tech Support

The following section features ressources and tips on software and hardware specific for making video art.

## File structure
This is a file structure for all projects, inspired by motion designer [Johannes Larsen](https://www.johanneslarsen.com)

In essence, the idea is to bin everything relating to a project inside a master folder, with every file relating to that project nested inside subfolders.
This allows for easier management of files once a project is finished.
Because you start with a date, all projects will sort when browsed on your computer.

###Project folder name

```YEAR-MONTH-DATE PROJECTNAME```

Your could go with YY-MM-DD, but I've chosen to run YYYY-MM-DD because I also use this method for pictures - and I have pictures from before 2000.

If you don't know the exact date a project started, ballpark it: ```2021-11-XX Project name```.
 
### Folder structure 

All projects look something like this, with three folders for footage, renders and documentation and an arbitrary amount of folders for each app used.
 
```
2026-09-22 Project name
├── TD
├── RES
├── DV
├── Footage
├── Renders
└── Documentation
```

```Footage``` All the footage that is, or could be used in your project. Make copies if you source the files from other directories.<br>
```Renders``` Video files rendered from Blender, Da Vinci etc. You could also make subfolders for each app, but keeping the outputs collected makes it easier to process afterwards, e.g. for converting to DXV before using in Resolume.<br>
```Documentation``` For every file documenting your process. Having a documentation in all projects makes it easier to find behind-the-scenes material for later.<br>
```XX``` Every app you use in your projects, get their own subfolder. TouchDesigner = TD, DaVinci Resolve = DV, After Effects = AE and so on. Collate all the files you use in the app into its subfolder.<br>

The golden rule is to **stuff everything inside the main project folder**. Follow the substructures or don't, as long as you keep everything in the main folder. Linking projects to random files in random places ensures that when you try to move stuff off you computer onto a backup, projects will break.<br>
Think of it as if you had a seperate desk for every little hobby you did, one for knitting that sweater, one for making a scrapbook. When you're not working on a project, you put the entire desk into a storage room.



## Resolume

### [List of explanations of Resolumes built-in effects](https://www.pluginprofessor.com/node-library#video-effect)

## Mac specific
### Very weird colors on video output (purple and green)
Apple computers output colors in the YbPbPr colorspace, meaning that you sometimes get weird results when outputting to hardware that requires RGB. The image is stable but colors are tinted purple and green.

It is complicated to fix in software, as there are no options for toggling between YbPbPr/RGB in MacOS's settings. It will require modifying hidden system files to enable RGB, which is not that practical.

If you can not change the input colorspace on the receiving hardware (e.g projector), the best fix is to add a device that handles the color conversion, for instance a scaler or mixer like the RGBLink mini.

### Somewhat weird colors on video output (unsaturated)
If the colors are just a bit off, especially lacking saturation, then you can probably fix it by changing the color profile in  ```System Settings - Display - Color profiles```

### Orange dot
From MacOS Monterey and onwards, Apple introduced an orange/red dot in the top corner of all displays, to let you know if the microphone was in use. Resolume and MadMapper are some of the softwares that potentially has access to the mic, so it triggers the dot.
The sentiment is alright, if only you could remove it, especially on external displays. **But you can't.**

### iCloud
iCloud often adds confusing for Mac native artists, as the cloud service lets you think that files are present on your computer without them being stored locally. They will get downloaded on demand, but this can be confusing and tedious to control.
[Guide on how to disable iCloud](https://www.multcloud.com/tutorials/stop-specific-folders-from-syncing-to-icloud-2223-gc.html)

---

## Windows specific
### Weird colors on video output
If your computer has an integrated graphics card (iGPU) you may not be able to output the full RGB spectrum. This is usually the case on cheaper laptops.
This results in all colors being limited between the values 16 and 235, instead of the full range of 0 to 255. This means that black looks like a dark gray, and white looks a bit dull. Gradients might also look banded.
**For laptops with an iGPU it might not be possible to enable the full range of colors.**

On laptops with a dedicated graphics card (dGPU) this can usually be changed in the control software for that graphics card.<br>
For laptops with Nvidia cards: [Nvidia Control Panel](https://apps.microsoft.com/detail/9nf8h0h7wmlt?hl=en-GB&gl=DK) <br>
For laptops with AMD cards: [Adrenalin](https://www.amd.com/en/products/software/adrenalin.html) <br>
*You are looking for a setting for enabling something like "Full range RGB" or "HDR".*