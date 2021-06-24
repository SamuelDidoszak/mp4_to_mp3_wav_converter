# mp4 to mp3 / wav converter
Script extracts audio from all of the videos in the directory

## Dependencies
**ffmpeg** is required

Simply download latest version from [ffmpeg github](https://github.com/BtbN/FFmpeg-Builds/releases) and add ffmpeg.exe to the directory that is saved in **PATH**

## Usage
There are two ways in which the script can be used
- add the script to the directory with videos needing audio extraction
- add the script to the **PATH** enables calling it without moving it to the folder

In both cases, the usage is the same.
In the folder with videos needing extraction:

`convertWav -rm` (optional, removes all of the .mp4 files in the directory after audio extraction)

Audio files will be stored in the directory from which the script was called