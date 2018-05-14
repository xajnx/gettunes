# gettunes
Tk front-end for the python script youtube-dl

*Requires youtube-dl (get here https://github.com/rg3/youtube-dl)
*requires ffmpeg to convert to mp3


v0.1 - Basic shell program. insert link, get mp3
       - This version doesn't print the YT-dl progess hooks in real-time.
         when you click 'Go' the program initalizes but you will not see 
         output until YT-dl has finished it's thing. I'm not sure how to catch
         the hooks yet, but when I do it will be in the next release.
       - Since there is no menu yet, it's best to put the script in your Music
         folder and create a .desktop entry to access it. Future versions will
         allow user to choose where files are saved.

future versions-
 - radiobuttons to access more of the youtube-dl options
 - search function
 - edit name of file
 - file menu to give option to pick where file is saved
 - print youtube-dl progress hooks in real time

**Install**
*if you don't have youtube-dl installed: `$>pip3 install youtube-dl` 
*if you don't have ffmpeg: `$> sudo apt-get install ffmpeg`
put script into your ~/Music directory
create .desktop entry to access it, or run directly from the shell.
