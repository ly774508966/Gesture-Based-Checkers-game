**Gesture Based UI**
===================

**Students:**<br>
*Dara Starr - G00209787*<br>
*Christopher Weir - G00309429*<br>
**Course:** *Software Development*<br>
**Module:** *Gesure Based UI*<br>
**Lecturer:** *Damien Costello*<br>
**Galway-Mayo Institute of Technology**
****

**Checkers Game**
-------------
![enter image description here](https://cloud.githubusercontent.com/assets/8806515/24556394/14646e48-162c-11e7-8f8f-d1244497b03b.png)


Application  Overview
-------------
The application which we have created for the Gesture Based UI module is a checkers/draughts game made in [Unity](https://unity3d.com/) and Visual Studio 15 using [Leap Motion](https://www.leapmotion.com/). Our Checkers game has built in multi-player where two players can connect across two devices and play once internet connection is present. Also you are allowed to run it locally on your own machine and sit side by side playing. The user's will be able to use the mouse, touchscreen, their left hand or right hand where Leap is present to control the movement of the pieces.

Versions
-------------
**Checkers:** This folder contains the multi-player Leap version of our game.

**Checkers 2.0** This folder contains single-player non Leap version which we intend to add Cortana functionality to in the near future.

How To Run
-------------
There are two ways in which the project can be run. First browse to the Checkers\Builds folder. This folder contains a built version of the game. Simply run the Checkers.exe file which will launch the game directly on your PC.

The second way to run the game is as follows, first make sure you have the latest version of Unity installed on your PC. You can download the .zip folder using the clone or download button located above right. When you have successfully downloaded the project save it on your PC and open the project in Unity. This link [How to build a Unity projject](https://docs.unity3d.com/Manual/PublishingBuilds.html) will tell you exactly how this process is completed. 

For multi-player when the game is launched you will see a host and connect button. One player selects host and will have to send there machines ip address to the other player. Open a command prompt and type ipconfig as a command. Under the Wireless LAN Adapter Wi-Fi section you will find your IPv4 address which is the address you fellow player will need to enter into the connect field to allow multiplayer. 

Troubleshooting References
--------------------------
- [Building a UWP App in Unity using TcpClient](http://stackoverflow.com/questions/39299961/building-a-uwp-app-in-unity-using-tcpclient)
- [Can't use System.Net.Sockets.TcpClient for WSA](https://forum.unity3d.com/threads/cant-use-system-security-cryptography-x509certificates-system-net-sockets-tcpclient-for-wsa.393174/)

References
-------------
 - [Leap Motion](https://www.leapmotion.com/)
 - [Unity](https://unity3d.com/)
 - [Setting up a Unity3D project with Leap](https://developer.leapmotion.com/documentation/unity/devguide/Project_Setup.html)
 - [Cortana](https://www.codeproject.com/Articles/1094232/Making-your-game-stand-out-with-Cortana-on-Windows)
 - [Multiplayer Checkers Tutorial](https://www.youtube.com/watch?v=93o_Ad5C5Ds&index=2&list=PLLH3mUGkfFCVXrGLRxfhst7pffE9o2SQO)
 
 
