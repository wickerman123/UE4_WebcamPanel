# Webcam Panel
A simple editor utility that adds a customisable panel that displays a users's webcam. A fun little challenge from @Luos_83

## Installation
Simply put the WebcamPanel folder in your Project's Plugin folder "*yourproject/Plugins/WebcamPanel*"

## Useage
#### Setup
There's a little bit of setup required. Follow these steps:


 1. Open up the media player at "*/WebcamPanel/Media/MP_Webcam*"
 2. In the top left of the preview, select the folder icon and find your webcam 

      ![CaptureDevices](https://i.imgur.com/YXcBAKb.png)
 3. Copy the URl that is now visible

      ![MediaURL](https://i.imgur.com/GZq6Gom.png)
 4. Open up the StreamMediaSource asset at "*/WebcamPanel/Media/Webcam_MediaSource*" and paste the URL you just copied then save.

      ![enter image description here](https://imgur.com/9ZnYDKq.png)
 5. Now as long as these steps were followed correctly and no refrences were broken along the way, all you need to do now is run the editor utility at "*/WebcamPanel/EW_WebcamPanel*"

      ![GoodJob](https://imgur.com/HCTGT5B.png)

#### Options
Click the options button in the top left of the panel to control various options such as the mask, background and chroma key settings (I don't own a greenscreen so I can't guarentee this works well, sorry!)
![Options](https://imgur.com/8jWNbJa.png)



## Known Bugs

1. When entering PIE, the Webcam feed breaks. To fix this, press the refresh button on the panel. The same issue will occur on exiting PIE too. 
2. If the panel is present in the layout when the editor is started, the aspect ratio is incorrect. To fix this, press the refresh button on the panel.
3. It's janky, I know, it's just a little bit of fun.
