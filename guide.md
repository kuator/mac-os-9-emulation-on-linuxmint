# Mac OS 9 emulation on Linux Mint

Go to https://www.emaculation.com/forum/viewtopic.php?t=6553 \
Download sheep-shaver from this link www.open.ou.nl/hsp/downloads/SheepShaver_GCC44_SDL_Unix_29-07-2013.zip

![www.open.ou.nl/hsp/downloads/SheepShaver_GCC44_SDL_Unix_29-07-2013.zip](https://user-images.githubusercontent.com/25168308/140707623-e2bb0697-3c4f-42fc-8bd2-2f7dcad26942.png)

Go to https://www.redundantrobot.com/sheepshaver \
Download ROM file from https://www.redundantrobot.com/sheepshaver_files/roms/newworld86.rom.zip

![https://www.redundantrobot.com/sheepshaver_files/roms/newworld86.rom.zip](https://user-images.githubusercontent.com/25168308/140708149-d3e2fdad-1b5f-4a43-9ed8-25c1ea9bafda.png)


It's necessary rename the rom file to 'Mac OS ROM'
```
$ cd ~/Downloads
$ mv newworld86.rom Mac\ OS\ ROM
```


Download an Mac OS 9 iso from https://winworldpc.com/product/mac-os-9/90

![image](https://user-images.githubusercontent.com/25168308/140709237-a3b89e05-9d5d-4b49-88fa-97dd6c72854c.png)

The rest of the guide: https://www.youtube.com/watch?v=hwX-QMPqrRg \
How to enable sound: https://www.youtube.com/watch?v=-uealjJ2YCQ \
Extra info if needed https://marstella.net/?p=219 \

Before running sheep-shaver, run `sudo sysctl vm.mmap_min_addr=0`
