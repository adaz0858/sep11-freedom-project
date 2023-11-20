## 11/13/23 Entry 1: Deciding on Tool
### Content
I am currently in the first stage of the **Engineering Design Process** which I have to **Define the Problem**. The problem we chose to solve is boredom and time consuming games. Lots of kids are getting sick and tired of those short boring games but are interested in those long, time consuming shooting or parkour games. Those children would be stuck in a round of game without being able to leave midway until an hour or so. Therefore, Angela decided to create a small but fun parkour game for those children who likes to play parkour games while I create background music for her game so the player won't feel bored.

The tool that I chose to use for my **freedom project** is [EarSketch](https://earsketch.gatech.edu/landing/#/) because I really enjoy listening to music and although I'm not creative, I still want to try and find the creative side of me. Making music in general does not seem fun since there's no type of music I'm aiming for, and just making music in general wouldn't be a fun experience if there's no reason why I'm making it. I was also interested in game making so I chose to collab with Angela so she can mainly make the game while I create the background music for her.

I tinkered my tool by first following the [tutorial](https://youtu.be/IzTgY1SLqgo?si=GlAS1P64U9yB-f2p) on YouTube on how to use **EarSketch** and I tried to do what the person did in his video and created a simple but random music. I named my file `random.js` and created this:
```js
setTempo(120);
var guitar1 = AK_UNDOG_ACOUSTIC_GUITAR_1
var bass4 = AK_UNDOG_BASS_4
fitMedia (bass4, 1, 1, 3)
fitMedia (guitar1, 2, 1, 5)
fitMedia (bass4, 3, 1, 3)
```
After getting my music to load, I had to find a way to embed my music from **EarSketch** into **cs50.dev**. I then watched another [video](https://youtu.be/UHjTXLAS4tU?si=GEOdSMgSJWmH1yAG) on how to use `<audio>`. However, I realized that I couldn't directly embed my link from **EarSketch** into the file in **cs50.dev** and needed a mp3 file. I had to watch another [video](https://youtu.be/UbhdenVCgRs?si=dYNC149-12D1Xg2C) on how to make my **EarSketch** into an mp3 file. After beign able to download my music and save it as an mp3 file, I had to learn how to embed it into my `html` file. I went to search up on how to create an [mp3 file]