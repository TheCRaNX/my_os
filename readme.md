# my_os

Based on tutorial from https://github.com/nanobyte-dev

Link to tutorial: https://www.youtube.com/watch?v=9t-SPC7Tczc&ab_channel=nanobyte

## Requirements

### Main

To run the operating system following software is needed:

- ubuntu
- any text editor
- Make
- nasm - assembler
- qemu

Install using:

apt install make nasm qemu
snap install micro --classic

Start using:

./run.sh

### Debug

To run the debugger for the operating system following software is needed:
 
- bochs
- vgabios

Install using:

apt install bochs bochs-sdl bochsbios vgabios

Start using:

./debug.sh
