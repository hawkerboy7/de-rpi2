# de-rpi2


## What is it?
`de-rpi2` has all files you need to get the a touchscreen working on a raspbery pi 2 B+. It also contains the NodeWebkit linux-arm so you can use NodeWebkit as well.

I did not create any of this but collected it from various sources, since it took me about a week to get everything the way I wanted I put everything online for others to save time.


## How to get it running?
___This will be described soon, for now use the following___
<br><br>
You can check: [Engineering(DIY)](http://engineering-diy.blogspot.nl/2013/01/adding-7inch-display-with-touchscreen.html)
This is the main source I used to get this thing up and running.
The '__Compiling the Kernel__' part you won't have to do.
Those files are provided in this repository.
You can skip to '__Replace the kernel__'
<br><br>
___Warning___: Don't try to replace `start.elf`. It is left out on purpose. If you do replaced it, the RAM memory of your Rpi2 will most likely become about 120mb. It's probably due to a bug in the start.elf file from `raspberrypi/firmware/archive/next.tar.gz`