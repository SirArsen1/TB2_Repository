# Tech Basics II Final Assignment: ~~Arduino MP3 player~~ Dino Game Console
The process of working on my final project was a rollercoaster of wins and losses.
However, to not bore the reader with the story, I will share the results right away and tell the process of doing the assignment later.

# The Result
The tutorial used for the creation of the project:
https://www.youtube.com/embed/PAu-gWs_lD8?si=tx3RlvOOmUWqwnMs
The code of the project, which was modified for this project:
https://techtalkies.in/2025/03/24/arduino-dino-game/?i=1

I decided to create a gaming console. It was a strong project, so I put as much effort into it as I could. However, time constraints and low morale still got in the way, as well as, of course, poor planning.
The console can play only one game: the one that mimics the famous "Google Chrome Dino Game". 


# The Process
## Act I. The Idea: 
Originally, I wanted to build an MP3 player and emphasized the visual presentation. Put it in a nice case. I always wanted to make a project like that, and it also appeared fairly challenging for a final assignment.
After my research, I decided to go with DFPlayer, an established MP3 module in arduino community that was also relatively cheap and allowed flexibility in designing the final project.
## Act II. The Excitement:
I knew an MP3 player is a challenging project, but I did not anticipate the horrors I was about to endure, and thus I was in a blissful ignorance, joyously designing concepts for mp3 player case, from which I would've planned my further purchases.

<img width="6529" height="2888" alt="image" src="https://github.com/user-attachments/assets/41f82c7d-fef0-439e-8800-688c2bc1c08c" />

## Act III. The Feigning Hope
First, when I plugged the wires in, I managed to get just a noise, nothing else. I thought it was normal, and I probably made a mistake somewhere; nonetheless, I saw that as progress. But then, I couldn't get a sound for a day or two, then weeks, then months. I failed to make the DFPlayer module work. Even with the help of the teacher, I could not squeeze even a little sound, besides the cracking noise from the module. Despite all connections being correct.
We considered that maybe the two modules I bought were faulty or broken, so I bought new ones. To my dismay, they broke too. The deadline was coming closer and closer, yet the project was not being done. 

![IMG_2493](https://github.com/user-attachments/assets/98fa0108-ccf5-450a-91d4-bc55e414295f)

## Act IV. The Change of Plans.
At this point, I have no time to order new parts; parts for Arduino projects take a particularly long time to arrive, which did not make things better. I felt terrible for backing down, but there was no way to fight it. I decided to cut loses and change my project to something different, that I can build from the starter kit I had. That is when I settled on making a game console for google chrome dino game.

<img width="526" height="296" alt="image" src="https://github.com/user-attachments/assets/9f656e05-c5bd-4fce-bf01-b6501ed9a5e0" />

The project was very simple to set up on a breadboard; therefore, I decided to try and do more with it, to make it as small as I can. I started planning soldering, how I would connect everything, cutting the cables, but when I was ready, it did not work. I tried to find the issue, but had too little experience to confidently say. Moreover, my morale was pretty low. My theory is that some copper strips or solder iron blobs somehow still interfere each other signal, considering that the LCD screen failed to lit up.

![IMG_2489](https://github.com/user-attachments/assets/032a6d8b-1951-4c7a-9836-474a13fa7eea) 
![IMG_2473](https://github.com/user-attachments/assets/d450b24a-36a3-45eb-9f8f-88e206c615c9)
![IMG_2472](https://github.com/user-attachments/assets/4df4d3b8-40b2-4cbd-ba15-db582aa3ca43)
<img width="3040" height="2644" alt="image" src="https://github.com/user-attachments/assets/3a697b98-7ec4-4ecb-ba8b-4e0ec34b383e" />
![IMG_2476](https://github.com/user-attachments/assets/9fc5b5ef-3e42-4355-a34e-5928bd29d0f4)
![IMG_2479](https://github.com/user-attachments/assets/f4d2c741-c357-4517-b9b6-3b0ed8ffaa6f)
![IMG_2478](https://github.com/user-attachments/assets/dfdda876-562e-4bdc-b466-de369f2fccfc)

Taking this into account, I decided to use three mini breadboards, and just minimize the space it takes by putting mini-boards on top of Arduino Uno (Because my last nano broke in the process of testing, which added another hurdle to my plans), using 3D printed supports, and then creating an outer enclosure for the whole project. I didn't have time to implement a mobile battery, unfortunately, so it has to be connected to a computer or a power bank to work.

![IMG_2490](https://github.com/user-attachments/assets/e7aa4bfe-c7f2-43f2-ab89-46bcffbb40b1)
![IMG_2485](https://github.com/user-attachments/assets/b31ce4d2-20d8-450f-97e9-e5531cf19829)

## Act V. The Conclusion:
I deliberately put as many wires as I could away from the button, so that the console can be played without any substantial discomfort. The choice of one button, was also intentional, yes, the tutorial uses one button, but initially I wanted to add on/off button, but had to scrap that. If I could I would've got rid of potentiometer, but it was too important for the comfort of the player.
I also had to settle for open case, the wire bending proved to be a no go option, that damaged the work of the code. The button is just too small. Even the simplest project had unforeseen problems and I had to make the best of the cards I was given,
Overall, I think it was a great experience (not always pleasant, though), I learned a lot nonetheless. I familiarized myself more with soldering and planning it, 3D printing and Fusion 360. I would like to continue this as a hobby to make more interesting projects, that I can use in everyday life. Hopefully I come back to the idea of creating an MP3 player later.
