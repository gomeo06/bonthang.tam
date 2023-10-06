
 Work in progress. Expect bugs.

Building
The game currently supports two different platform-backends: SDL2 and Sokol. The only difference in features is that the SDL2 backend supports game controllers (joysticks, gamepads), while the Sokol backend does not.

Linux
Ubuntu
# for SDL2 backend
apt install libsdl2-dev libglew-dev
make sdl
# for Sokol backend
apt install libx11-dev libxcursor-dev libxi-dev libasound2-dev
make sokol
Building The game currently supports two different platform-backends: SDL2 and Sokol. The only difference in features is that the SDL2 backend supports game controllers (joysticks, gamepads), while the Sokol backend does not.

