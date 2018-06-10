iRemoteDesktop, a Screen Sharing Software for Windows. (Prototype)


The project builds and runs successfully in its current state, though it might be a bit slow. 
This project is pretty old and bloated. 
I have a slimmer option that is fast but lacks some of the functionalities that is included here.
Important differences between Screenshare and RemoteDesktop: RemoteDesktop has UDP hole punching implemented; ScreenShare does not and only works locally. RemoteDesktop uses a mirror driver for screen capture; ScreenShare does not and uses the native Windows Desktop Duplication API available in Windows 7/8/10
iRemoteDesktop brings the remote computer to you, with extra tools like a remote file manager, registry editor, and chat.


Technical Features & Libraries courtesy of-
* C#
  * [Lidgren UDP networking library](https://code.google.com/p/lidgren-network-gen3/) for basic UDP functionality
  * [Ermau's Tempest networking library](https://github.com/ermau/Tempest) (modified) for a more object-oriented architecture
* [DFMirage mirror driver](http://www.demoforge.com/dfmirage.htm) for extremely fast screen capture
