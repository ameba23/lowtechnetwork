
# using ranger for playing music

i love ranger and i love mpd (music player daemon).  While there are some good mpd clients available, its good to be able to play music directly from a file manager because other file operations can be performed to organise the collection as well.  and because rangers interface is powerful and familliar to me.  i still use ncmpcpp for managing playlists. 

pms (practical music search)

i already have keybindings in my window manager to toggle pause, skip and seek with mpd so it is not really needed to add these to ranger. but i put this one in anyway:

map . shell -f mpc seek +5
map , shell -f mpc seek -5

## adding to ranger


* keybinding to jump to currently playing song (from wiki)
* embedded cover art previewing using ffmpeg
* wrapper to colourise exiftool, for when no cover art is available. exiftool provides a lot of information and i can be difficult to see the tags which are most interesting (title, artist, album)
* keybinding to play tracks and directories (recursively) even if they are outside of the mpd database directory.  

