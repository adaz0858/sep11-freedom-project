# Tool Learning Log

Tool: EarSketch

Project: Making the background music for Angela's game using EarSketch. After making my background music, I will learn ImpactJS and help Angela with creating some other parts of her game. (Where the characters catches stars and has to count the amount of stars they have so if they input the correct amount at the end, they win, but if they insert wrong amount then they lose. There would also be mobs so if the characters touches one then they lose all the stars and have to recount).

---

10/29/23:
* I watched a [YouTube tutorial](https://youtu.be/IzTgY1SLqgo?si=89TvcnY47OiMtb9m) on how to use ``EarSketch using JavaScript and I learned a tip to create a variable for each beat so I won't have to manually change everything.
* I tried, on `EarSketch`, to set up a `var` for a soundtrack and played it using `fitMedia(sound, track, start, end)`. I used the piano sound track and named it piano1. I didn't know what "track", "start", and "end" meant so I gave it different numbers. I found out that track just means what row I want my cound to be on, start is the measure where my sound starts on, and end is the measure where my sound stops on. I first tried `fitMedia(piano1, 1, 1, 2)` but the music sounded short so I changed the ending measure to 3 and it sounded more complete. I tried to change the track number to 2 to see what would happen but nothing really happened other than the sound moved from row 1 to 2.
* While typing in `fitMedia()`, I saw many other codes, I wonder what those codes are for and if I would ever have to use those. If those aren't codes then I wonder if what those are, are they just the sound names?

11/13/23
* I watched a [video](https://youtu.be/UbhdenVCgRs?si=dYNC149-12D1Xg2C) on how to make EarSketch into an mp3 file.
* Then I searched on [google](https://beta.reddit.com/r/cs50/comments/1742soy/uploading_mp3_files_to_my_final_project_folder/) for how to insert my mp3 file of the song I created in EarSketch into cs50.dev.
* Lastly, I watched a [video](https://youtu.be/UHjTXLAS4tU?si=GEOdSMgSJWmH1yAG) on how to use `<audio>`.
* Next time I want to check out other functions EarSketch has such as `makeBeat()`.
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

11/19/23
* Didn't really tinker too much but I looked over all the possible codes I can use in API of EarSketch.
* I used another sound where a lady was singing and created an mp3 file.
    * I found out that there will be lyrics on the bottom of the screen.

11/25/23
* I watched this [video](https://youtu.be/WA_Ci2ZtuRM?si=lZ-AS0B9XYczzU_L) on YouTube to learn what insertMedia does because I know how to use fitMedia, but I'm still learning the other functions.
* I learned that fitMedia and insertMedia are similar except for insertMedia does not have an end measure meaning it only plays the sound once.
    * This means that insertMedia is most useful when you want the sound you chose to play the whole thing without having to wonder how many measure it takes up.
    * I went on earSketch to try out insertMedia by using the first guitar sound that I used in my fitMedia before but insertMedia was better since I didn't have to replay the sound many times to see when the measure ends. 
* My next step is to watch more videos on YouTube on the other functions and trying to make something using those functions.