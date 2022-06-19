# Monday 2 May
---
At SITSound. Came around an hour early, so I’m just going to note down any info I might need later about how the first group’s doing their stuff.

-   Took a few minutes to get reasonably-loud live feedback from the booth, so expect to find some potential difficulty with that in the studio.
-   Some of the knobs are master knobs, so others are also various components of the same effect. Like how a ProTools plugin is edited by shifting various virtual knobs.
-   Once you get good at using the desk, you don’t need to use ProTools’ Mix window much, if at all. There’s a little section of knobs that apparently have the same overall function as the Mix window. 
-   The three small monitors on the desk are for showing your audio tracks, their current volume and inputs etc.
-   Sometimes the feedback issue can be solved by a save and restart (old reliable, flipping the switch off and on again).
---
![[602 May 2 - Drawing.png]]
-   _I drew a bumblebee🙂 with my fingers💅_
---
-   Some of the master knobs influence a whole section of the desk.
-   First step of doing any of this is making sure the software is responding to the hardware.
-   The headphones are probably gonna be a bit finicky on occasion.
-   Rightmost module is preamp.
-   Input VB1,2,3= Vocal Booth 1,2,3
-   Audio is stereo- not in surround sound, only “5.1” because the studio is set up as 5.1
-   Main module only controls what we hear through the edit room speakers- not actual recording tracks
-   Talkback (Cue1+2 input) is turned on and off with ‘Talk’ button. Don’t use during line checks, as the talkback will conflict with whatever’s being recorded. You can change the volume through the preamp module and main module.
-   Red dead clip is in downloads folder.
-   First steps for recording:
	-   Set up mic
	-   Set up talkback
	-   Set up actor’s reference
  
---
## Pics from inside the studio
![[602 May 2 - Picture of Studio 2 Equipment 1.png]] 
![[602 May 2 - Picture of Studio 2 Equipment 2.png]]
![[602 May 2 -  Picture of Studio 2 Equipment 3.png]]

---
## PDF of handout sheets explaining how to use ProTools in Studio 2 (pictured above)
![[Handout sheets explaining how to use ProTools in Studio 2.pdf]]

---
## Annotation of handout sheets explaining how to use ProTools in Studio 2 (pictured above)

### **Studio 2 Setup and Operation

**Powering up the studio and getting Pro Tools working

1. Turn on the Furman Power Conditioner. (In the rack to the right of the desk)
2. Turn on the computer. (Left of desk - Power button at bottom right on computer)
3. Turn on TV monitor at the back of the room. (Remote on right windowsill)
4. If a menu pops up at the bottom of the TV monitor, push the home button on the remote to make it disappear.
![[602 May 2 - Document Figure 1 - TV Screen Menu.png]]
_Fig. 1: TV Screen Menu_
5. Log into computer. 
	Account: protools, Password: minder
---
6. DADman software should open automatically upon logging in. This software MUST be open with the correct monitor profile loaded for Pro Tools to playback sound.
![[602 May 2 - Document Figure 2 - Blank DADman Profile.png]]
_Fig. 2: Blank DADman Profile_
7. In DADman, go to File > Open Profile and click on the file called "Studio 2 DADman Profile.dmprof". This should be sitting on the desktop.
---
8. Upon opening the profile, the first 4 faders in the 3rd bank on the desk should
automatically move up. The monitoring section on the desk (Top right of Master
Module) should also come up with levels for MAIN and Cues.
![[602 May 2 -  Document Figure 3 - Monitoring section on desk after DADman profile has been loaded..png]]
_Fig. 3: Monitoring section on desk after DADman profile has been loaded._

---
9. DADman on the computer should look as below:
![[602 May 2 - Document Figure 4 - DADman Profile Loaded.png]]
_Fig. 4: DADman Profile Loaded
10. If the faders don't move at all check under Settings that EuCon has been ticked.
![[602 May 2 - Document Figure 5 - DADman EuCon Enabled.png]]
_Fig. 5: DADman EuCon Enabled
1. Open Pro Tools
---
**Your First Recording.

![[602 May 2 - Document Figure 5.1.png]]
1. In Pro Tools create a new 48kHz 32bit session. 
   ![[602 May 2 - Document Figure 5.1 1.png]]
2. Create a new Mono, Audio Track in Pro Tools.
   ![[602 May 2 - Document Figure 5.1 2.png]]
3. Make sure the input of the new track is set to the input that matches the microphone you are trying to record.
4. Make sure the output is set to the main output for the studio.
5. Record Arm the track.
   ![[602 May 2 - Document Figure 5.1 3.png]]
6. You should now see a little bit of signal in the meter.
7. To get more signal, use the gain knob on the PreAmp to the raise the signal so it is splashing in the green.
8. At this stage get the talent to read their script at their loudest volume. Make sure the signal never gets close to the top of the meter.
9. To record press the Play and then the Record button on the S6 console.
10. To stop press Space Bar
---
**Setting up Headphones

![[602 May 2 - Document Figure 5.2.png]]
1. On the same track go to the Send section and create a new send to Cue 1-2
![[602 May 2 - Document Figure 5.2 1.png]]
2. Turn the send fader up to 0.
   ![[602 May 2 - Document Figure 5.2 2.png]]
3. Now you should be seeing signal on the track, in the headphone send fader and at the headphone amplifier in the rack.
4. And you should be able to hear the signal by plugin in a pair of headphone to the headphone return in the vocal booth.

---
**Talkback
![[602 May 2 - Document Figure 5.3.png]]
1. The talkback mic is in channel 8 of the PreAmp and must have phantom power. (The +48V button must be lit up.)
2. Make sure channel 8 on the pre amp is turned up.
3. Then click the 'Talk' button on the S6 to turn the mic on.
![[602 May 2 - Document Figure 5.3 1.png]]
4. You should now hear the talk back in the headphones.
---
Basic Troubleshooting
- No sound:
	- Load the default 10 profile for Studio 2: Setup > 10 > Import Settings > Select "Studio 2 Default 10"
	- The desk should reflect any new tracks created in Pro Tools and be able tocontrol what is happening in Pro Tools. Example below. If that does nothappen go to Setup > Peripherals > Ethernet Controllers and make sure that "Enable EUCON" is ticked.

![[602 May 2 - Document Figure 6 - S6 when EUCON in Pro Tools is enabled. If EUCON is not enabled the desk will be unable to control Pro Tools..png]]
_Fig. 6: S6 when EUCON in Pro Tools is enabled. If EUCON is not enabled the 
desk will be unable to control Pro Tools.

- If the monitoring section on the Master Module goes blank for whatever reason, clicking into DADman should bring it back.

- Desk Connections:
---
- Upon logging into the computer, the desk should automatically connect to S6 WSControl, which is indicated by a spinning circle in the top right of the screen as it loads. It should look as below once connected:

![[602 May 2 - Document Figure 7 - S6 WSControl connected to Master Module.png]]
_Fig. 7: S6 WSControl connected to Master Module

- On the Master Module, under Settings > Workstations, the screen should look as below if connected properly:

![[602 May 2 - Document Figure 8 - Master Module Workstation Connected.png]]
_Fig. 8: Master Module Workstation Connected

---
- If WSControl does not connect properly check the following settings on both the computer and Master Module.On the computer, click on S6 WSControl > Network Setup and check that the settings look as below:

![[602 May 2 - Document Figure 9 - WS Control Network Setup.png]]
_Fig. 9: WS Control Network Setup

- On the Master Module under Settings > Surface > Cog Icon, check the settings look as below:

![[602 May 2 - Document Figure 10 - Master Module.png]]
_Fig. 10: Master Module Surface Settings

---
- 
	- Once these are fixed, on the Master Module go to Workstations and checkthat the computer (MAC-ZAST2-2001) is under the "Connected" heading.
	- If not, grab the computer under "Network" and drag it across the screen to one of the slots under the "Connected" heading. See Fig. 8.

- Monitoring Section: See Fig. 3.
	- The knob under MAIN controls the level of the speakers.
	-  The knob under Cues controls the level of the headphone signal.
	- Holding down the Talk button engages the talkback mic for the duration ofhow long it is held down. Pressing the Talk button will dim any signals goingto Cue.
	- The talkback mic runs through channel 8 on the Audient preamp. This meansChannel 8 must constantly have phantom power enabled and have the gainturned to 12 O'clock. Please leave these settings untouched even whenzeroing the desk and shutting down the studio.

![[602 May 2 - Document Figure 11 - Talkback Mic on Audient Channel 8.png]]
_Fig. 11: Talkback Mic on Audient Channel 8_

---
**Powering down the studio

- On the Master Module go to Settings > About > Shut Down to power down theMaster Module. This must ALWAYS be done first when powering down the studio.

![[602 May 2 - Document Figure 12 - Shutdown Menu for Master Module.png]]
_Fig. 12: Shutdown Menu for Master Module

- Shutdown the computer. When closing DADman always click “Don't Save Changes" when it asks.
- Once the computer is off switch off the Furman Power Conditioner.
- Cover the desk/screens with sheet.
- Turn off lights/air con.
- Close all doors including the door with the keypad on it. Make sure this door is pulled firmly shut behind you.
