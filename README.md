# cpp-compile
Fun little bash script that compiles and runs C++ programs when it detects a change in `*.cpp` files from the current (or sub) directory. Not groundbreaking, just an exercise to alleviate excessive compiling for small programs.

## Dependencies
- inotifywait
  - Arch-based distro: `pacman -S inotify-tools`
  - Debian-based distro: `apt-get install inotify-tools`

## Usage
Run the script in the directory for which you want to listen for file changes. It will run continuously until stopped.
