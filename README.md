# Adding text to video

Small bash script that uses ffmpeg to add text subtitles to video with a
transparent background box.

Reads from TSV file with the columns `start, end, text`, where start is when the
text starts being displayed, end is when the text stops being displayed, and
text is the text that is displayed.

e.g.
```
10	20	Welcome to my video
21	30	This is an introduction to...
```
