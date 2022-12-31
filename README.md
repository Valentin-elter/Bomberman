# Bomberman

Second year study project, a cross platform 3D bomberman-like made with raylib (Windows/linux).

## Features

All the mechanics of a classic Bomberman
Saves management
competitive A.I.
local multiplayer
Cross Plateform (Windows/Linux)

## Build with linux (ubuntu)

Realised with Raylib 3.7.0

### 1. Install required libraries and tools:

	sudo apt install build-essential git
    sudo apt install cmake
    sudo apt install libasound2-dev mesa-common-dev libx11-dev libxrandr-dev libxi-dev xorg-dev libgl1-mesa-dev libglu1-mesa-dev

### 2. Download the Rqylib source code and extract it:
	https://github.com/raysan5/raylib/releases/tag/3.7.0

### 3. Build and install Raylib:

    cd raylib/src/
    make PLATFORM=PLATFORM_DESKTOP
    sudo make install

### 4. Build bomberman from my repo:
	cmake .
    make
	./bomberman


## Screenshots

![Alt text](screenshots/1.png?raw=true "1")
![Alt text](screenshots/2.png?raw=true "2")
![Alt text](screenshots/3.png?raw=true "3")
![Alt text](screenshots/4.png?raw=true "4")