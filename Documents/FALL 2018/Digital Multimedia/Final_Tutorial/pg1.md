#  __Sampling and Bit Depth__ 
---

* [Home](https://github.com/haleyheidenreich/Digital_Tutorial/tree/master/Documents/FALL%202018/Digital%20Multimedia/Final_Tutorial/README.md)
* [Page1](https://github.com/haleyheidenreich/Digital_Tutorial/tree/master/Documents/FALL%202018/Digital%20Multimedia/Final_Tutorial/pg1.md)
* [Page2](https://github.com/haleyheidenreich/Digital_Tutorial/tree/master/Documents/FALL%202018/Digital%20Multimedia/Final_Tutorial/pg2.md)

---
## __Sampling Audio__

### Sampling takes a certain amount of audio and/or video signal at a very fast rate. The quality of this sampling is determined by the sampling rate (aka bit rate). 

| Sampling | Sample Rate |
| --- | ---|
| Capturing the amplitude over time | The amount of samples per second |

### The higher the bit rate used, the bigger amount of samples you'll have per second, hence a better sound or video. 
### A CD for instance is usually sampled at 44.1 kHz, or 44,100 samples per second. So, during a second into the CD-audio there were 44,100 samples taken. 

[Watch this video](https://www.youtube.com/watch?v=BNVVq-iVPy8)

## __Bit depth__ 
---
### Bit depth is the resolution of the single sample rate. A bit is a 0 or a 1 in value, and more bits that are present in the sampling, the higher resolution it will be. 

### For the sampling rate above for the CD-audio file, it was being sampled at 44.1 kHz and the bit depth for a standard CD is 16 bits. 

### **Ideal Range** for kHz per sample rate is usually around 44.1 - 48 kHz with a bit depth of 24.
### There are two channels in audio: mono and stereo. 
### Mono is where all of the audio recorded is being channeled through one audio channel. 
### Stereo is when there are two audio signal channels that can go into different sets of speakers to produce what seems like a reproduction of the original sound however it can create a lot of perspective and depth. 

---

Mono-->[One Signal Channel] 

Stereo -->[ Signal One ]
Stereo -->[ Stereo Two ]

![Mono and Stereo](https://github.com/haleyheidenreich/Digital_Tutorial/blob/master/Documents/FALL%202018/Digital%20Multimedia/Final_Tutorial/mono-stereo.jpg)

---
## __Frequency__

### The human ear can hear patterns of frequencies between about 20 Hz and 20,000 Hz. 
### Hence, why the sample rating of about 40,000 Hz is the minimum to produce sounds within the range that humans can hear because we have to take the sampling rate and double it to produce a digital sample audible to humans. 
### Here is a list of the common sample rates measured in Hz:
* 8000
* 16000 
* 22050 
* 44100 
* 48000 
* 96000 
* 192000
---
## __Dynamic Range__ 
---
### Dynamic range is the differenciation of the volume between the loudest and softest sounds.
### It is measured in decibels (**dB**), for humans we can only hear anything that is at least 90 dB. 
---
A list of common sample formats for dB:

| bit | decibels (**dB**) |
| --- | --- |
| 8 | 48 |
|16 | 96 |
| 24 | 145 |
| 32 | infinite | 

---

[**More information on Dynamic Range and Sampling**](https://manual.audacityteam.org/man/digital_audio.html)

* [BACK TO HOME](https://github.com/haleyheidenreich/Digital_Tutorial/tree/master/Documents/FALL%202018/Digital%20Multimedia/Final_Tutorial/README.md)
* [PAGE 2](https://github.com/haleyheidenreich/Digital_Tutorial/tree/master/Documents/FALL%202018/Digital%20Multimedia/Final_Tutorial/pg2.md)




