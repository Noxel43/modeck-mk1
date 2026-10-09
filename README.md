# modeck. mk1

*A fully open-source, DIY MP3 Player*

## Core Features:
- Loads of buttons (9) that are each mappable
- ~~Lovely tactile feel~~ (I lie, currently, for prototyping, I'm just using 6mm tacts, however, I really want to incorporate keyboard switches)
- Physical EQ. A potentiometer (currently twist, but I will make it slide) that controls the EQ
- Colour LCD screen (170x320 res)
- USB-C charging (I plan to incorporate pogo pins on the back)
- SD card for storage - easily transfer songs
- Stereo audio (why am I mentioning this, who wants a mono mp3 player?)
- 2 Layer PCB. The PCB consists of only two layers, so its cheap to produce.
- Possible WiFi/BT. For the PCB, I am using the ESP32-S3-WROOM, which has WiFi and a built in atenna. It's not currently a priority, but streaming, or at least downloading from wifi would be cool.

## Core Components:
***Note:** This is the list of* main *components, not a full BOM, which will be added later.*
- ESP32-S3-WROOM
  - This is the main MCU, i.e. the brains
- ES8388
  - This is the audio codec, handling all of the audio output
- Waveshare 1.9" LCD screen, SKU: 23822
  - Used as the screen (duh). Can be substituted for any 1.9" screen.
- Battery
  - I'm writing this on my school laptop and I can't remember what I'm using specifically, but it's a LiPo. Watch this spot.

## Specifications:

placeholder

## Timeline:

#### **Current Phase:** Prototyping & EVT

*making sure everything works, not yet usable by public*
***Timeframe:** next month or two*

**Current:** PCB design done

**Next:**
- [ ] Make basic firmware for audio playback only
- [ ] Add input handling for all buttons
- [ ] Add a GUI for the screens
- [ ] Add EQ

#### **Next Phase:** DVT & Release

*design validation test, i.e. adding the case, etc*
***Timeframe (from phase start):** ~1 month*

- [ ] Create enclosure
- [ ] Ensure easy printability and assembly
- [ ] Publish v1 with guides, etc, ready without a polished firmware, if people want to make their own.
- [ ] Polish firmware, add different modes, and a good UI/UX
- [ ] Release full.
