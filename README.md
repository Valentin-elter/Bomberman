# Bomberman

A second-year student project, a cross-platform 3D bomberman-like game developed using the raylib library, compatible with Windows and Linux operating systems.

## Features

* Incorporates all the mechanics of a classic Bomberman game  
* Includes a save management system  
* Features competitive AI opponents  
* Offers local multiplayer functionality  
* Compatible with both Windows and Linux operating systems  

## Build with linux (ubuntu)

Built with Raylib 3.7.0

### 1. Install required libraries and tools:

	sudo apt install build-essential git
    sudo apt install cmake
    sudo apt install libasound2-dev mesa-common-dev libx11-dev libxrandr-dev libxi-dev xorg-dev libgl1-mesa-dev libglu1-mesa-dev

### 2. Download the Raylib source code and extract it:
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