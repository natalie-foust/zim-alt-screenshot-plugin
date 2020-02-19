# Alternate Insert Screenshot Plugin

This is a custom Zim plugin that builds off of the built in Insert Screenshot plugin and provides necessary functionality. This plugin adds in the option to minimize Zim right before taking the screenshot, allowing users with one screen to take screenshots of programs hidden under Zim's window.

### Installation

1. Move the plugin file `insert-screenshot.alt.py` to `~/.local/share/zim/plugins/`
2. Open up Zim and in `Edit>Preferences>Plugins` 
   1. Disable `Insert Screenshot` 
   2. Enable `Insert Screenshot (Alternate)` and configure it as you need.



### Compatibility

This plugin works for me running Zim 0.72.0 running xorg in Kali linux. Sorry if it doesn't work for you but honestly this was just a way to procrastinate from the work I should actually be doing. 

I included a patch file that shows the differences between my plugin and the built in plugin so if insert-screenshot-alt.py doesn't work, look at the changes I made and see if those can still be made in similar places.

### Credit

I was inspired to do this by [Osndok's plugin](https://github.com/Osndok/zim-plugin-screenshot2) that tried to fix the same problem but did not work with my version of Zim. I took pieces from their code.

I obviously made very few changes to the original Insert Screenshot Plugin which was built by Jaap Karssenberg