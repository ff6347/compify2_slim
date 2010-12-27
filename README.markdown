// compify2_slim.jsx
==
// This is for using the effect: *Keylight 1.2* on tons of greenscreen images
--
// =====================================================================  
// compify2_slim.jsx for After Effects CS4/CS5 by fabiantheblind Nov 2010 based on:  
//  
// compify2.jsx by Joseph M. Morgan - April 2005 based on:  
//  
// Compify.jsx Byron Nash, Edited and Improved by Paul Tuersley  October 2004  
//  
// Stripped of most UI stuff. Thanx to the great documentation and the straight structure within the code    
//  
// **To script does as follows:**  
// 1. make a selection in project window. -> this must be on the lowest level of the project window needs fixin    
// 2. make a target folder (with prompt)  
// 3. make a comp of every item in selection with 12 fps, 1 frame long, in the footage size  
// 4. apply a effect preset. -> The applied Preset has to be in the same folder as the script  
// 5. adds the comp to the renderqueue as singleframe. and sets the render location -> the render presets have to exist  
//  
// **bugs:** has to work from everywhere not only lowest level of proj window  
//       this seems to be a bug in compify and also on compify2  
//       also the last version at Byron Nashs website: COMPIFYv5.JSX  
//       http://www.armoredsquirrel.com/scripts/COMPIFYv5.JSX  
//       seems also to have this bug  
// **bugs:** exit() and stop() won't work  
//   
// _todo:_ an external xml or json file or txt to read in the variables.  
// _todo:_ build the render templates  within  
// =====================================================================  
  
