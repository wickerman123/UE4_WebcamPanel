# Webcam Panel
A simple editor utility that adds a customisable panel that displays a users's webcam. A fun little challenge from @Luos_83

## Installation
Simply put the WebcamPanel folder in your Project's Plugin folder "*yourproject/Plugins/WebcamPanel*"

## Useage
To open the panel, make sure you enable "Show Plugin Content" in your content browser, then Navigate to "*WebcamPanel Content*" and run "*EW_WebcamPanel*"

<img src="https://imgur.com/CQBr11W.png" height="250"> <img src="https://imgur.com/WInEUZh.png" height="250">

#### Options
Click the options button in the top left of the panel to open the options menu. Here you can select your input device, control various options such as the mask, background and chroma key settings (I don't own a greenscreen so I can't guarantee this works well, sorry!)
![Options](https://imgur.com/VZVQXcr.png)



## Known Bugs

1. Not all devices are supported - this is an issue with the Media Framework in UE4 and not something I can personally fix. OBS VirtualCam is not supported and my own Logitech C270 while detected by UE4, returns a blank stream with no error messages. (Smarter folk feel free to submit pull requests if you know how to fix it!)
2. If the panel is present in the layout when the editor is started, the aspect ratio is incorrect. To fix this, press the refresh button on the panel.
3. It's janky, I know, it's just a little bit of fun.
