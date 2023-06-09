# How to install yeast.

![](https://user-images.githubusercontent.com/94982718/230476773-eafbe948-ef00-4543-907e-e0939a26c653.png)

First, you want to make sure that `ack` is installed on your system:

`sudo apt-get install ack` for Debian-based distros

`sudo pacman -S ack` for Arch Linux

`brew install ack` for MacOS

To install yeast, clone this repo by doing:

`git -C ~ clone https://github.com/shebangcode/yeast`

Then, you want to go into the yeast directory:

`cd yeast`

Next, if you want to have yeast as a command, do:

`sudo cp ~/yeast/yeast /bin`

The command above is only optional.


Here is a list of the flags:

`-h`: Shows all the flags

`-a`: Searches for hidden and normal files

`-r`: Searches recursively in directories for files

`-z`: Searches recursively in directories for hidden and normal files

Here is the official ack website, if you want to check it out: https://beyondgrep.com
