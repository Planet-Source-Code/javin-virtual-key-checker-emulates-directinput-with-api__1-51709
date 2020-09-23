<div align="center">

## Virtual Key Checker \(emulates DirectInput with API\)


</div>

### Description

I want to appologize in advance for the complete lack of commenting, or direction with this code. Note that this is for ADVANCED users. If you can't figure it out, I don't want to hear it. I didn't actually intend to post this for other people, so I didn't take any steps to make it easier to use, but I got to thinking maybe someone else can use it.

This uses only Windows API but has most of the same functionality as DirectX's InputEngine. Even quite a bit of functionality that DirectX's Input Engine doesn't have. About the only thing it doesn't do is joysticks. (Yet.) Believe it or not, the speed is actually comperable to DirectX too, and I often use this instead of the DirectX InputEngine in my DirectX apps.

It's fairly simple and straightforward (which is good since there's no accompanying examples). You create an instance of the class, and if you want to see if a key was pressed since the last time the object was called, you would check the value of VKObject.Pressed(VK_KEYNAME). Has handlers for mouse functions too.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |2004-02-13 02:51:42
**By**             |[Javin](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/javin.md)
**Level**          |Advanced
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Games](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/games__1-38.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[Virtual\_Ke1708042132004\.zip](https://github.com/Planet-Source-Code/javin-virtual-key-checker-emulates-directinput-with-api__1-51709/archive/master.zip)








