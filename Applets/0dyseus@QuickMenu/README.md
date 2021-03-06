## Quick Menu applet description

The function of this applet is very simple, create a menu based on the files/folders found inside a main folder (specified on this applet settings window). The files will be used to create menu items and the sub folders will be used to create sub-menus.

## Compatibility

Tested and working on Cinnamon version 3.0.7.

## Features

- More than one instance of this applet can be installed at the same time.
- A hotkey can be assigned to open/close the menu.
- Menu items to .desktop files will be displayed with the icon and name declared inside the .desktop files themselves.

## Options

![Settings window](https://raw.githubusercontent.com/Odyseus/CinnamonTools/master/Applets/0dyseus%40QuickMenu/public/Screenshot-001.png "Settings window")

#### Applet settings

- **Choose main directory:** Choose a directory with files and/or folders in it. The files will be used to create the menu items. The folders will be used to create sub-menus.
- **Custom Tooltip:** Set a custom tooltip for the applet.
- **Show Applet icon.:** Display this applet icon.
- **Icon for Applet:** Set a custom icon for the applet.
- **Show Applet title.:** Display this applet title.
- **Title for Applet:** Set a custom title for the applet.

#### Menu settings

- **Keyboard shortcut to open and close the menu:** Sets a hotkey to open/close the menu.
- **Icon for sub-menus:** Set a custom icon for the sub-menus.
- **Autoupdate menu.:** If enabled, every time the menu is opened, the applet will scan the main folder for added/deleted/modified files/folders and rebuild the menu. If disabled, the menu has to be updated manually from its context menu.
- **Show only .desktop files:** If enabled, only .desktop files will be used to create the menu. If disabled, all file types will be used to create the menu.
- **Show hidden files:** If enabled, hidden files will be used to create menu items.
- **Show hidden folders:** If enabled, hidden sub folders will be used to create sub-menus.
- **Show sub-menu icons:** If disabled, all sub-menu items will be created without icons.
- **Show menu items icon:** If disabled, all menu items will be created without icons.
- **Ignore sub folders:** If enabled, the sub folders found inside the main folder will be ignored and sub-menus will not be created.

## Known issues
**Note:** My very limited knowledge (I'm not a developer) along with the lack of documentation for creating applets makes the corrections of these bugs/issues very hard for me. If someone has the solution, don't hesitate in pointing me in the right direction.

- Some file types (.log for example) will create menu items without icons.

<h2 style="color:red;"> Bug report and feature request</h2>
<span style="color:red;">
Spices comments system is absolutely useless to report bugs with any king of legibility. In addition, there is no notifications system for new comments. So, if anyone has bugs to report or a feature request, do so on this applet GitHub page. Just click the **Website** button next to the **Download** button.
</span>

## Change Log

##### 1.00
- Initial release.

