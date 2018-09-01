Wallsplash
==========

Set Unsplash images as wallpapers with colorscheme support.


Install
-------

#### From AUR:

    yaourt -S wallsplash

#### From sources:

Install [`feh`](https://feh.finalrewind.org/), [`wal`](https://github.com/dylanaraps/wal) and [`unsplash-wallpaper`](https://www.npmjs.com/package/unsplash-wallpaper).

     git clone git@github.com:filalex77/wallsplash.git
     cd wallsplash
     cp ./wallsplash /your/path/of/choice

Usage
-----

    Usage: wallsplash [OPTIONS]

    Options:
        * wallpaper type:
            -r,--random
            -a,--daily
            -e,--weekly
            -f,--featured
            -q,--search     Get a photo from a search query
        * colorscheme options:
            -c,--colors     Set colorscheme with wal
        * file options:
            -s,--symlink    Create symlink to wallpaper
                            in /home/<USER>/.current_wallpaper

    Example:
        wallsplash --featured -cs

License
-------

wallsplash is licensed under the [GPLv3 Public License](https://github.com/filalex77/wallsplash/blob/master/LICENSE).
