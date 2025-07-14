# minion-hackathon-submission
Everybody loves minions... and so do we! We wanted to make a minion in real life. That's exactly what we did! 

This project did not go as planned, to say the least. We were initally planning to do an Octocat or Orpheus, but it seemed unfeasible to model and a lot of other teams were already doing that. We spent all of Friday night brainstorming and finalized our idea at exactly 7:52 AM on Saturday, 7/12/25. We then began work on our project and demoed this:
<img width="1017" height="735" alt="image" src="https://github.com/user-attachments/assets/9a88eace-f2b5-49aa-8d31-b656d75c31e5" />

I (@pizzalover125) worked on the electronics and @dld worked on the CAD. By evening, even after completing some of the workshops, the displays, CAD, AND speaker all worked!
<img width="693" height="360" alt="image-removebg-preview" src="https://github.com/user-attachments/assets/8bec8da1-1a06-4d81-8df2-4bc770b28562" />

It should have been easy sailing from here... right? Nope, not even close. First of all, the 3d printer situation was a DISASTER. Everyone had prints and it was just super chaotic. I tried soldering neopixels FOR HOURS but it just wouldn't work. I then began work on the microSD, which was the start of the disaster. Me and my partner then went to sleep. 

The next day was very unproductive and its hard for me to even say what happened. Firstly, we had only one USB-C cable which was super annoying. I continued work on the MicroSD and it worked!!! I then tried soldering neopixels again for an hour or so. Did. not. work. I came back and decided we should add a soundboard thing. We first tried an old macropad PCB. We worked on that for a bit, but it was just hard to use. We then pivoted to 12mm Push Buttons. That was a whole lot easier. But for some reason, the microSD just stopped working. We still do not know what happened. We tried and tried, and then just decided to use a Raspberry Pi Zero. We attemped to connect to the TVs in a couple of rooms, but that did not work. We thought about using SSH, but then just realized we didn't even need microSD cards at all. We could just compress everything! Meanwhile, the eyes in the displays weren't blinking. We then realized we could just make them identical. We did not do this at the start because we wanted a terminator mode. Speaking of things we wanted at the start, we also wanted to have the minion say hello whenever someone walked by. However, that just seemed like an additional layer of complexity that may not even work with so many people walking around. We just scrapped that...

TBD
