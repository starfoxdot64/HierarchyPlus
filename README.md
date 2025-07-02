Plugin by @Dreadrith 

Streisand Effect by Barbra Streisand, 2003

-- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --

# [Install Instructions]
These are a little different than before, I'm not going to put together a VPM add page or anything like that - this is gonna be static.

- Open the Unity Package Manager
- Go to `Window > Package Manager > Plus Icon (top-left corner) > Add package from git URL
- Paste in this repo's Git URL: https://github.com/starfoxdot64/HierarchyPlus.git
- Let Unity cook for a minute

If you wanna do it a little more manually, download the release on the right and extract it to a folder, and pick "Add package from disk" instead. You'll need to pick the package.json included in the zip file, it's the last one Dreadrith released before nuking his repo list.



-- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --


# HierarchyPlus
A general improvement to the Unity hierarchy window such as component icons, guide lines, row coloring and settings for customization.


![](https://i.imgur.com/w1uNB7O.gif)
## Features
- Enhanced hierarchy view: Component icons, guide lines, row coloring, and other.
- Left click components to toggle on/off.
- Right click components to open their context menu.
- Toggled objects and components can be recorded for faster clip creation.
- Easy custom icon support for any component.
- Settings window for customization and coloring.


## Custom Icons
You can change or add your own icons for components. Here's how to do it:  
1- Hover over the icon of the component whose icon you want to change.  
![](https://i.imgur.com/if4bi2P.png)

2- Find the CustomIcons folder under `Packages > Tools - HierarchyPlus > CustomIcons`  
![](https://i.imgur.com/xMjNENk.png)

3- Add your icon into that folder and give it the same name as the component that it belongs to.  
![](https://i.imgur.com/TCPyfY1.png)|![](https://i.imgur.com/QzU3D7c.png)
-|-

4- You may have to refresh the Icons to see the effect immediately. Find HierarchyPlus settings window under `Tools > HierarchyPlus`, and click `Refresh Icons`
