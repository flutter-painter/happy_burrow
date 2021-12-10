# youtube-dl.md

brew install youtube-dl
brew install ffmpeg


youtube-dl -x --audio-format mp3 --audio-quality 0 -o '/Users/mac/Music/%(artist)s_%(title)s.%(ext)s' https://youtu.be/xSE1W0Zaa3U

***


https://github.com/ytdl-org/youtube-dl


-f, --format FORMAT   VS -x, --extract-audio  
--audio-format FORMAT                Specify audio format: "best", "aac",
--audio-quality QUALITY              Specify ffmpeg/avconv audio quality, (use 0 for best)
// playlists are all downloaded automatically 