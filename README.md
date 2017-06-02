# Labyrinth Game

Labyrinth is a cross-platform game for Terminal/Command Prompt.

Tested under Ubuntu 16.04, Windows 10 and macOS 10.12.5.

*__Please note:__* The game *may* as well work under other operating systems.


## Installation

Currently there are two known ways to run the game:

* Locally build the program
* Run the executable for your system

### Installation: Build program
Simply clone the repository and build it with the following:

    git clone https://github.com/paper-lark/labyrinth && cd labyrinth && make
    
The executable can be found in the **bin/** folder.

*P.S.* For this method make sure you have ```gcc``` compiler installed. On Windows I would recommend using **MinGW** to archieve that.

*__Please note:__* The program depends on ```pdcurses``` (Windows) or ```ncurses``` (Linux, macOS) library. 
Thus, make sure to install ```nucurses``` library if you are going to run the program on Unix-like system;
on Windows just make sure that ```pdcurses.dll``` library that is located in **bin/** folder is located in the same folder as the executable.

### Installation: Run prebuilt executable
Simply find the appropriate executable in the **bin/** folder: **labyrinth.mac** for macOS, 
                                                               **labyrinth.linux** for Linux,
                                                               **labyrinth.exe** for Windows.
                                                                 
Please take a look at the note in the previous section - same rules apply here.

## Bugs
If you find any bug, please report it at https://github.com/paper-lark/Labyrinth/issues

## Suggestion
If you have any suggestions about the project or new features, feel free to contact me.

## License
Labyrinth is available under the terms of the MIT License. See ```LICENSE``` for more.