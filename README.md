<p align="center"><img width="600px" src="http://i.imgur.com/tXmKntN.png"/></p>
<p align="center">-----------------------------------------------------------------------------------------------------------------------</p>
<p align="center"><img width="300px" src="http://i.imgur.com/WDZye0M.png"/></p>
USV (Universal Smart Video), as the name says, is a format for smart/interactive videos. We can call it "the video of the future".
<p align="center"><img width="300px" src="http://i.imgur.com/7ETTqEs.png"/></p>
Do you imagine if we have the power of <a href="https://youtube.com" target="blank">YT</a>'s videos in a file on our devices? A USV file can have credits to the authors, multiple language subtitles/audios, indicative rating, tags, etc. All it embedded in a single video file! Please read more in SPECS.md to know.
<p align="center"><img width="300px" src="http://i.imgur.com/iIvVFpt.png"/></p>
A .USV file is just a compressed archive with the extension changed, containing this structure:
<p align="center"><img width="800px" src="http://image.prntscr.com/image/dc79febda9bc4c7ea58745be539e701d.png"/></p>

The images/frames can be in both PNG or SVG, and the audios in both OGG or FLAC. All other infos are stored in XML files.

Folders:

AUDIO folder contains the audio files (or a unique audio file) or the language folders containing the respective audios.

Except the files (images), the same occurs in the FRAMES folder. The files need to be named in crescent numbers.

The IMG folder contains the images that will be used in the video, such as tags, the thumbnail, etc.

Files:

AUDIO.XML contains the time each audio will be played. In case of only one audio file, a unique tag will tell that it will start at 00:00.
<p align="center"><img src="http://image.prntscr.com/image/a10329b5e56e485f8179adfeaee2f558.png"/></p>

FRAMES.XML constains the time a quantity of frames will be played till a frame-number.
<p align="center"><img src=""/></p>

INFO.XML contains infos about the video, such as the version (of the format), credits, main language, if it is fictional, indicative rating, if it is paid and if it is a muted-loop video (alternative to GIF).
<p align="center"><img src=""/></p>

TAGS.XML contains the type of tag and the time it will be played.
<p align="center"><img src=""/></p>
