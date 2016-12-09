# Homematic-Virtual-Interface Sonos Plugin

This plugin creates a 19Key Remote for every Sonos ZonePlayer
Map the first 18 Keys in the device settings to sonos commands:

Play, Pause, Next, Prev, VolUp, VolDn, Spotify

To do that open the device settings in webgui there is a field called CMD_PRESS_SHORT. setup the commands there for the specified key.
The spotiy command is a little special. Setup the playlist you with to play in the CMD_PRESS_LONG field for that key.

Press the key and the plugin will execute the command.

There is a special Channel 19 and it will change in the future.
This channel contains currently 2 parameters 

TARGET_VOLUME, PLAYLIST

you may set the PLAYLIST Parameter with a playlist url (currently spotify only is supported -> eg : spotify:user:spotify_germany:playlist:1dPjXhd0s7DBTCuaolLVSm)
and the current queue will replaced by this playlist and the zoneplayer will play that list.