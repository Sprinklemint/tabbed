tabbed - generic tabbed interface
=================================
tabbed is a simple tabbed X window container.

Requirements
------------
In order to build tabbed you need the Xlib header files.

Installation
------------

    sudo make install 

Running tabbed
--------------
See the man page for details.

# Screenshots

<img src="https://cdn.discordapp.com/attachments/610012463907209227/803169215690965043/unknown.png">
<img src="https://github.com/siduck76/personal-backup/blob/master/rice%20flex/tabbed1.png">  
<img src="https://github.com/siduck76/personal-backup/blob/master/rice%20flex/tabbed2.png">
 
# Quick use 

     open ST terminal with tabbed mode :  tabbed -c -r 2 st -w ""  (make a keybind for this)  
     
     open new tab : Ctrl + shift + enter <br>
  
  check the config.h for few more keybinds 
 
 - NOTE : tabs will open appear only if more than one ST window is opened . 
 - customize tabbed colors via xresources 
 
```
  example : 
  
  tabbed.selbgcolor:   #282c34
  tabbed.selfgcolor:   #d6d8eb

  tabbed.normfgcolor:  #9294a8
  tabbed.normbgcolor:  #353b45
  
  ```
