# Welcome to GameFuse Unreal Example

## Overview
This Unreal Engine project is a seamless integration of the GameFuse online subsystem plugin, allowing developers to effortlessly incorporate authentication, user data management, leaderboards, in-game stores, and more into their projects without the need to write or host any servers or API code.


## Getting Started
 - The first step of integrating GameFuse with your project, is to make an account in [Gamefuse.co](https://gamefuse.co/)
 - Clone the project ([How to clone a Git LFS project](https://www.youtube.com/watch?v=AuFsGlY3wvA&t=118s)).
```sh
git clone https://github.com/game-fuse/game-fuse-unreal-example
```
 - [Download](https://github.com/game-fuse/game-fuse-cpp/releases) the Plugin and unzip it or you can [Download it from the the Unreal Store](), then add to this project in the Plugins folder and Enable it inside the Engine.
 - in Content/GUIApplication/Blueprints > BP_GUIGameMode, input your GameID and GameToken within the 'Set Up Game' node. 
- Within your Game Fuse account, include some cars as store items. Then, add these cars along with their corresponding IDs to the DefaultPawnClass map variable located in Content/SampleGame/Blueprints > BP_PlayerController.

![cars](https://res.cloudinary.com/dgwqhqk47/image/upload/v1699827059/static/CarUnrealExampleScreenshot.png)

 - Muscle ![cars](https://res.cloudinary.com/dgwqhqk47/image/upload/v1699827059/static/CarUnrealExampleBlack.png)

 - Sport 1 ![cars](https://res.cloudinary.com/dgwqhqk47/image/upload/v1699827059/static/CarUnrealExampleYellow.png)

 - Sport 2 ![cars](https://res.cloudinary.com/dgwqhqk47/image/upload/v1699827059/static/CarUnrealExampleREd.png)

- Press the play button and run the example

## License

 *  Copyright (c) 2023-11-06 GameFuse
 *  All rights reserved.
 
