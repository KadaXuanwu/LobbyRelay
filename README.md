# LobbyRelay
This unitypackage provides an implementation of the Lobby and Relay services. It can be used to get started faster with Unity multiplayer, and is meant to be used together with Netcode for GameObjects.
The package comes with scenes for creating / joining lobbies and also a lobby room.

To use it, the following steps have to be done:
- Log in to Unity Gaming Services, go to the 'Projects' tab and create a new project. Then go to the 'Multiplayer' tab and activate Lobby and Relay.  https://dashboard.unity3d.com/organizations/9071185473635/settings/projects
- In your Unity project, make sure you have the packages 'Lobby', 'Relay', 'Netcode for GameObjects' and 'Authentication' from the Unity Registry installed, as well as TextMeshPro Essential.
- While installing the packages, you should get prompted to link your Unity project to the Gaming Services. If not, you can do it under Project Settings -> Services.
- Import the LobbyRelay.unitypackage into your project.
- Add the scenes to your build settings. Make sure that the Login scene is at the top.

At this point, you should be able to build the game and join the same lobby on multiple clients.

The 'Game' scene just serves as an example and can be replaced by your game scene/s.
The script Database.cs contains some useful variables like MaxPlayers, CurrentPlayerCount, ClientIds, InGame, etc., which will also get updated accordingly.

Have fun!
