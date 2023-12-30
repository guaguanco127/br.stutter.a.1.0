# Ableton Max for Live device: br.stutter.a.1.0



By Brian Riordan  
[guaguanco127@gmail.com](mailto:guaguanco127@gmail.com)  
[brianriordanmusic@gmail.com](mailto:brianriordanmusic@gmail.com)  
[https://www.brianriordanmusic.com/](https://www.brianriordanmusic.com/) 
  
Repository for br.stutter.a.1.0, with all related files, can be found here: [https://github.com/guaguanco127/br.stutter.a.1.0](https://github.com/guaguanco127/br.stutter.a.1.0)  
Additional programs can be found here: [https://github.com/guaguanco127/plugins](https://github.com/guaguanco127/plugins)

These files were created with Max/MSP version 8.5.6. 

## Table of Contents 

[About](#About)  
[What is a Max for Live Device?](#M4L)  
[How To Install](#Install)  

## <a name="About"></a>About

A Max for Live device that is built around the Max/MSP stutter~ object. A real-time granular glitch effect that is a signal capture buffer.

For a more complex version of this effect, try [br.stutter.a.1.0](https://github.com/guaguanco127/br.stutter.a.1.0) or [br.stutter.c.1.0](https://github.com/guaguanco127/br.stutter.c.1.0)
  
**On/Off:** When Stutter is turned on, the signal is interrupted and a history of the signal is repeated based on the grain size. 

**Button:** While the stutter is on, pressing the button acts like a re-trigger, capturing another grain of the live signal that was fed into the stutter at the time, regardless of what the stutter was just playing. There is no feedback option. 

**Speed:** The playback speed of the grains. 1.0 is the default and is normal speed. Negative speeds play the grains backwards. The range is a float from -32.0 and 32.0. 

**Latent Mode:** When "Latent" is on, the stutter waits to record the next grain of sound before switching to the next stutter sound. The latency is equal to the next grain size. This is a valuable feature because it captures what comes next, as opposed to what already has come and gone. Turning the latent mode off captures the previous grain size prior to pressing the re-trigger button. The default is on. 

**Mix Mode:** There are two mix modes, "Gate" and "Insert" with "Gate being the default. "Gate" allows the dry unaffected signal to pass through while the stutter effect is turned off. The dry signal then mutes once the stuter is turnes on. This feature is best in an effects chain. The "Insert" mode does not allow any dry signal to pass through while the stutter effect is turned off. Instead, you only hear the grains play once the effect is turned on. This feature is useful for auxilliary effect return tracks. 

**Size:** The size, in milliseconds, of the current grain that is playing. "Size 1" is compared with "Size 2" and a random size is chosen between these two parameters. The range is between 5 ms and 1000 ms. This is only a meter that tells you its size, you cannot adjust it. 

**Size 1:** The first potential size timings. "Size 1" is compared with "Size 2" and a random size is chosen between these two parameters. The range is between 5 ms and 1000 ms. The default is set to 5 ms.

**Size 2:** The second potential size timings. "Size 1" is compared with "Size 2" and a random size is chosen between these two parameters. The range is between 5 ms and 1000 ms. The default is set to 1000 ms.



## <a name="M4L"></a>What Is a Max For Live Device?

Max For Live brings the power and flexibility of Max to Ableton Live. Max For Live gives you access to hundreds of exclusive custom plug-ins (Live Devices) as well as the tools to build your own. These can be MIDI and audio effects, audio and video synthesizers, 3D Jitter visuals, as well as tools that interact with the Live application itself, via the Live API.

## <a name="Install"></a>How To Install

1. Make sure you have the Ableton Live Suite installed in your computer. This was tested on version 11. Make sure Ableton is turned off while installing. 

2. For Macintosh:  
Go to your user folder  
Then Music > Ableton > User Library > Presets > Audio Effects  
Copy and paste br.stutter.a.1.0.amxd into that folder

3. For Windows: \Users\[username]\Documents\Ableton\User Library\Presets\Audio Effects\Max Audio Effect     
  
4. Open Ableton Live. On the left-hand side, look for Max for Live > Max Audio Effect and then the name of this device.

5. Either double-click on the device, or drag/drop it onto the track where you wish to use it.  
    



 





