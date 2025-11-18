
INFO:

V3 was a bridge between V2 and V4 a near-complete re-write, a hybrid of sorts, turned into V4.

V2 was the ORIGINAL HUD. It was made of spaghetti code and got too hard to keep up with.

V1 was a bit of a test. An eyeball that followed you with music and a stylized display. This was the original vision, not you seeing the world but rather a Curious AI (HA! The name!) watching you. Spaghetti code so bad I need to rebuild it to get it to work. It was meant to learn dynamically based on what it saw and researched, was created about a month or so before LLMs blew up.

Vista and Base were attempts at making a "DIY modular" version of the HUD and assistant. It did not work.

The "Assistant" branch is a bit of what Vista and Base tried to be, made stuff modular and made V3 become V4.

The experimental assistant branch I think was the test for adding Yolo V5 rather than V3, and I am fairly sure I didn't finish and it got abandoned and broken, I kinda just implimented it without testing and this branch wasn't really needed.

V4 Is the current in-development version, it's near complete, it needs a splashscreen, clock, subtitles, translation, auto-lobotomizer (IMPORTANT), and possibly a log mode (like V2).





BELOW IS MOSTLY OUTDATED INFORMATION ON AN OLD BUILD OF V2 MAY OR MAY NOT STILL WORK:


This is the Curion HUD and AI assistant for Python, it can be used on Debian-based Linux desktop systems and windows probably to build custom heads-up-display headsets. It is made with YOLO V3/V5! Also modular now with a voice assistant and voice changer and so much more!

1. Ignore all these steps it's all outdated, you are all on your own.
   
2. Install the required things using CurionV2/darknet/Curion downoad.py

3. Launch CurionV2/darknet/Curion-HUD.py

4. Fiddle with cv2.VideoCapture(0) and change 0 to different values until your camera shows up on startup

#IF MAKING HEADSET

4. Make Curion-HUD.py launch on startup by modifying .bashrc file to run the Curion-HUD.py

5. You can use Teamveiwer, duct-tape, a wireless camera, a phone-vr headset, a phone, and more duct-tape to test until you build hardware
