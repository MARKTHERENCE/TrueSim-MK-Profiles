# TrueSim-MK-Profiles
Various amp schematics translated into .TXT files, made for the guitar amp sim plugin "[TrueSim]( https://nalexsoftware.blogspot.com/2022/07/truesim-simulator.html )" developed by [NaLex Software]( https://nalexsoftware.blogspot.com ).
Circuits are made with TrueSimCircuit, potentiometer knobs are rearranged via text editing.

## IMPORTANT!
Only the preamp circuits are ported. You will need a 3rd party power amp sim after. Below are the ones I would recommend:
- [Ignite Amps TPA-1]( https://www.igniteamps.com/#tpa-1 )
- [NaLex PowerBox]( https://nalexsoftware.blogspot.com/2020/05/powerbox-poweramp.html )
- [Nick Crow Lab TubeDriver]( https://nickcrowlab.blogspot.com/2009/08/tubedriver-v10.html )
- ["Poweramp" section from deLuther's Genie]( https://guitarplayer.ru/guitar-studio/plaginy-st-rock/ )

Refer to the [README.md from the Amplex-MK-Presets]( https://github.com/MARKTHERENCE/Amplex-MK-Presets/tree/main#setting-up-the-power-amp ) for instructions on how to set them up.

# List of Amp Models
This collection covers a wide range of amplifier types based on gain amount, voicing, etc. This is never set in stone as I may add more amp models at any given time.

## Single Channel
- Marshall Vintage Modern 2266/2466
- Paul P's Bogen CHB-35A Amp Conversion
- Sovtek MIG-50
- Supro 1690T
- Trainwreck Liverpool

## High Gain
- Ceriatone Plexi 100 Super Lead Dookie Mod
- MESA/Boogie Mark V (Channel 3)
  - I intended to write all the channels but this amp model is quite CPU intensive in particular, even with x0.5 oversampling nor multithreading. This will be brought up to NaLex at some point.
- Orange #4 TT15 Jim Root Terror

## Multi Channel
- Cornford MK50 II
- Gibson Super Goldtone GA Series
- Ibanez Thermion TN120
- Kitty Hawk Quattro Preamp
- Krank Krankenstein
- Laney Klipp 100
- Legend Rock 'n Roll Series
  - The "1st & 2nd Stage" and "3rd Stage" circuits must be used together for the amp model to work as intended. This was done to compensate for the maximum number of visible pots that TrueSim could support.
  - For the "Lead Mode" channel, adjust the Input gain by +6dB or the Input knob at 6 (1 o'clock), which is equivalent to a +18dB boost.
- Marshall Silver Jubilee
  - For the intended "rhythm clip" effect (diode clipping), adjust the Input knob at 6 (1 o'clock), which is equivalent to a +6dB boost.
- Orange Rockerverb
- Orange Thunderverb
- Peavey Triple XXX

# Special Thanks
- [Every person mentioned in the Special Thanks section of the README.md from the Amplex-MK-Presets repo]( https://github.com/MARKTHERENCE/Amplex-MK-Presets/tree/main#special-thanks )
- [Heavy metal chainsaw]( https://www.youtube.com/@cmd_f5 ) for helping me catch up with version updates.
- [Omega Station]( https://www.youtube.com/@OmegaStationMusic/videos ) for sharing the Amplex presets and subsequently making me keep track of TrueSim's development.
- NaLex for helping out with troubleshooting on the Marshall Vintage Modern circuits
