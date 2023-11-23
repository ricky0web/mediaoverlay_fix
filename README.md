# mediaoverlay_fix
Hello. I am attempting to create a fixed-layout EPUB with Media Overlay support. However, it is not functioning as expected. Below is a description of the work I have done and the issues I am encountering.

Implemented Steps:

Used InDesign to add images for each dialogue over a single-page comic.
Exported the EPUB using InDesign.
Created an audio folder and stored mp3 files in it.
Prepared a SMIL file, linking XHTML file IDs with mp3 files and specifying the start and end times for each dialogue's audio.
Specified each item in the <manifest> tag of the OPF file.
Zipped all files using 7zip and changed the extension to .epub.
Confirmed Issues:

Opened the EPUB file in Adobe Digital Editions, but the audio did not play.
Opened the EPUB file in Thorium Reader, but the audio did not play.
Attempted Solutions:

Entered alt="alternative text" and found that Thorium Reader played the phrase "alternative text" for each dialogue.
Note:
I have uploaded the created files and the EPUB file to GitHub.
https://github.com/ricky0web/mediaoverlay_fix
