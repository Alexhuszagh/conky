# Conky Files

## Acknowledgements

* This is a fork of [Infinity Dark Conky Theme] (http://icanbeacoder.com/blog/infinity-conky-version-2/) by harshit.

## Install

* Install conky
    ```shell
    # apt-get install conky-all
    ```

* Download the source files and copy to your home folder.
* Toggle all the "1600" values in .lua/scripts/haunted.lua to fit your desktop geometry (my screen is 1900x1280, so adjust accordingly).
* Edit lines 29-30 in .conkyrc from to your screen size.
    ```
    minimum_size 1920 1280
    maximum_width 1920
    ```

* Toggle the settings (such as replacing "wlan0" with "eth0" for your system.)
* Load by running:
    ```
    conky &
    ```

## Images

The rest of the of the configuration files can be found in my settings [Awesome WM] (https://github.com/Alexhuszagh/awesome) and [Dot Files] (https://github.com/Alexhuszagh/dotfiles).

![Image of functionning dock]
(http://i.imgur.com/auyIM0A.png)
![Image of tiled and floating dropdown terminals]
(http://i.imgur.com/ZqAPFi4.png)
