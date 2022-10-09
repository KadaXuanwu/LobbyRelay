# LobbyRelay
This unitypackage provides an Implementation of the Lobby and Relay services. It can be used to get started faster with Unity multiplayer, and is meant to be used together with Netcode for GameObjects.
The package comes with scenes for creating / joining lobbies and also a lobby room.

To use it, the following steps have to be done:
- Log in to Unity Gaming Services, create a new project and activate Lobby and Relay. https://dashboard.unity3d.com/organizations/9071185473635/projects/96132d57-11d7-49df-9d33-4c86fc83e61c/environments/c24c1eea-d540-40c2-8065-0ea2e2741340/multiplay/about
- In you Unity project, make sure you have the packages 'Lobby', 'Relay', 'Netcode for GameObjects' and 'Authentication' from the Unity Registry installed.
- You should get prompted to link your Unity project to the Gaming Services. If not, you can do it under Project Settings -> Services.
- Import the LobbyRelay.unitypackage into your project.
- Add the scenes to your build settings. Make sure that the Login scene is at the top.

At this point, you should be able to build the game and join the same lobby on multiple clients.

The script Database.cs contains some useful variables like MaxPlayers, CurrentPlayerCount, ClientIds, InGame, etc., which will also get updated accordingly.

Have fun!
