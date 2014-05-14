# Some CLI tools

## youtube-dl-dir
Install `youtube-dl` orginal script on your machine (`sudo apt-get install youtube-dl`, `yaourt -S youtube-dl`).

Put the script `youtube-dl-dir` in to `/usr/bin` directory.

### Usage
```bash
$ cd ~/Videos

$ youtube-dl-dir http://www.youtube.com/watch\?v\=2Z4m4lnjxkY
[youtube] Setting language
[youtube] 2Z4m4lnjxkY: Downloading webpage
[youtube] 2Z4m4lnjxkY: Downloading video info webpage
[youtube] 2Z4m4lnjxkY: Extracting video information
[download] Destination: ./Trololo Sing Along!.mp4
[download] 100% of 7.18MiB in 00:03

$ ls
Trololo Sing Along!.mp4
```