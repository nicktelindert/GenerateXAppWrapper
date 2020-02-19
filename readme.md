# GNUStep/NextSpace AppWrapper Generator

By: Nick te Lindert
License: GPL2

## Description
Now that the GNUSTEP based NextSpace is in active development is found it a good idea to fill in the gap for adding existing applications.
This is a easy to easy bash script which converts XDG desktop files to a GNUstep XwrapperApp.

## How does it work?

Download the generate-app-wrapper from my github page.
Place it anywhere you want, for convenience copy it to /usr/local/bin.
Make it executable and run it with generate-app-wrapper -i inputdirectory -o .app folder locations.

## Issues?
This is the first bash script i ever wrote, so please give me some feedback on my script and report issues.

## Known issues
- svg and xpm support is not fully functioning
- Icons now are only searched for in /usr/share/icons
- File associations are not working yet
