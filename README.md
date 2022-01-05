IA-Device

An Arduino-based project which notifies the user of an entry into a room based on input from an ultrasonic wave sensor.

Inspiration: When the pandemic first hit, we were all forced to change the way we lived, worked, and in my case studied. 
  I enjoy listening to music when I work/study and since my back faces the door to my room, there were a few too many incidents where I was tuned in and couldn't hear someone entering my room.
  This device allows me to listen to music while being aware of my surroundings. The LCD screen and LED bulbs notify me whenever the door to my room is opened (NO MORE JUMP SCARES!)
  
How it works: The ultrasonic wave sensor sends out a sound wave and the transucer receives the soundwave and calculates how far the wave travelled based on the speed of sound.
  After some testing, I was able to determine the distance at which the wave travels when there is no obstruction at the entrance of my room (aka nobody is walking in). 
  When the distance changed (decreased) due to someone walking in, 2 LED bulbs would flash to catch my attention and the LCD screen located beside me would show a message notifying me that an entry has been detected. 
  Since the arduino needs to have the code uploaded and then needs to be powered on for the system to work, I used a 5V adapter (from an old phone) and attached it to the arduino and its USB connection. 
