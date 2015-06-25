#urxvt-tabbedex

"Tabbed" multiplexing plugin for the rxvt-unicode (urxvt) terminal emulator

##Resources

The following resources can be set in the `~/.Xdefaults` file.

```
tabbed.tabbar-fg            color of the tab-bar foreground
tabbed.tabbar-bg            color of the tab-bar background
tabbed.tab-fg               color of the active tab foreground
tabbed.tab-bg               color of the active tab background
tabbed.title-fg             color of the title foreground (text)
tabbed.title-bg             color of the title background
tabbed.tabbar-timeouts      background tab activity timeouts
tabbed.new-button           ???
tabbed.title                ???
tabbed.autohide             hide the tab-bar when there is only one tab
tabbed.no-tabbedex-keys     ???
tabbed.reopen-on-close      open a new tab after the last tab is closed
tabbed.index-from-one       open a new tab after the last tab is closed
```

##Commands

The following commands can be bound to keys in the `~/.Xdefaults` file.

```
new_tab         create a new tab at the next highest index
rename_tab      rename the active tab
next_tab        make active the next tab (eventually cycling around)
prev_tab        make active the previous tab (eventually cycling around)
last_tab        make active the tab at the highest index
goto_tab_nn     make the tab at index *nn* the active tab
move_tab_left   swap the active tab with that on the left
move_tab_right  swap the active tab with that on the right
```

##Differences from [stepb/urxvt-tabbedex](http://github.com/stepb/urxvt-tabbedex)

Modifications are listed in the script file itself for now in a style of the
upstream.

##LICENSE

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <http://www.gnu.org/licenses/>.
