 compify2_slim.jsx
==
This is for using the effect: *Keylight 1.2* on tons of greenscreen images
--
You can use any other Effect- / RenderSettings- / OutputSettings-Preset  
--
**compify2_slim.jsx** for After Effects CS4/CS5 by fabiantheblind Nov 2010 based on:  
 
**compify2.jsx** by Joseph M. Morgan - April 2005 based on:  
 
**Compify.jsx** Byron Nash, Edited and Improved by Paul Tuersley  October 2004  
 
Stripped of most UI stuff. Thanx to the great documentation and the straight structure within the code    
 
**The script works as follows:**  
- make a selection in project window. -> **this MUST be on the lowest level of the project window**   
- make a target folder (with prompt)  
- make a comp of every item in selection with 12 fps, 1 frame long, in the footage size  
- apply a effect preset. **-> The applied Preset has to be in the same folder as the script**  
- adds the comp to the renderqueue as singleframe. and sets the render location **-> the render presets have to exist**  
 
**bugs:** works only woth footage from lowest level of project window  
      this seems to be a problem in compify, compify2 and COMPIFYv5.JSX  
  
