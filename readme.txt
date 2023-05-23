
Candy Cruncher
Version 1.17
February 12, 2002
by Pyrogon

Distributed by RealNetworks, Inc.
RN Version 1.0

*************************
*** TABLE OF CONTENTS ***
*************************

I	System Requirements
II	Troubleshooting
III	Instructions
IV	Registration
V	Technical Support
VI	Credits
VII	Legal Stuff
VIII	Version History

***************************
I.  System Requirements ***
***************************

The following section lists the minimum and recommended system
specifications for Candy Cruncher:

For MICROSOFT WINDOWS:
- CPU: Pentium/166MHz or better

- RAM: 32MB RAM

- Operating System: Microsoft Windows 95(OSR2), Windows 98,
Windows ME, Windows 2000, Windows NT4 (SP3+) or Windows XP.

- Controls: A standard keyboard and mouse are required

- Sound: A DirectSound compatible sound card is required for
sound and music, however if no audio is present Candy Cruncher
will still play with sound disabled.

- Graphics: Candy Cruncher requires a 15, 16, 24 or 32-bit display


**********************
II.  Troubleshooting *
**********************

MICROSOFT WINDOWS:

Candy Cruncher requires Microsoft DirectX to be installed.  For
the latest version of DirectX visit:

http://www.microsoft.com/directx

If Candy Cruncher runs slowly in windowed mode, you may wish to
try switching to full screen (registered version only).  Alternatively, 
make sure your desktop is set to 16-bit color (also known as
"65536 colors" or "thousands of colors").


*******************
III. Instructions *
*******************

The object of Candy Cruncher is to line up and remove complete
rows or columns of candy.  Each level requires you to remove
a certain number of rows or columns before time expires.

Clicking on a candy adjacent to the blank space will swap
the blank space and candy.  The only exception is the Dreaded
Black Jellybean, which cannot be moved.  You can also use
the arrow keys on your keyboard to move the blank space.

HINT: Instead of clicking, you can hold down the mouse button
and "drag" the space around!  It takes some practice, but it
boosts your speed dramatically!

When a row or column is completed it disappears and the board
is adjusted appropriately.  In addition, every time a row or
column is completed you gain back some time on the clock.  The
number of points scored for a successful row or column completion
depends on the candy and the current level.

Later levels introduce the mystery candy, which acts as a "wildcard"
and can thus be used to fill in a missing piece.  For example, if
a row has 5 candy corns and a mystery candy, it will complete
the row.  In addition, the mystery candy has a powerful capability
when completing a row with a Dreaded Black Jellybean....

Registered Versions Only:

By clicking on the Fullscreen or Windowed button you can toggle
between fullscreen and windowed playing modes.  If you find that
the game is running slowly in a window, try it in fullscreen
mode.

By clicking on the Pause button you can stop the game's play.  A
"cover" will be placed over the playfield so that you can't
cheat by looking ahead!  In addition, if Candy Cruncher is
minimized or loses focus (for example, an "instant messenger"
window pops up while you play), it will automatically pause!

Finally, if your score is greater than one of the current high
scores, you will be prompted for your name so that your own score
can be recorded in the high scores list!

********************
* IV. Registration *
********************

If you enjoy playing the demo version of Candy Cruncher you'll
want to register it for new features!

You can purchase the full version from:

http://www.real.com/games/candycruncher/plus.html

************************
* V. Technical Support *
************************

In the unlikely event that you experience problems with Candy Cruncher,
you can contact us at:

http://customerrelations.real.com/scripts/rnforms/tech_service.asp

If you can, please include the following information along with the
description of your problem:

Computer manufacturer and type
Operating system
CPU Type and Speed
Amount of RAM
Soundcard Type
Videocard Type
Registration name and code (if applicable)

***************
* VI. Credits *
***************

Candy Cruncher was created by Pyrogon:

Programming:	
   Brian Hook

Art:
   Rosie Cosgrove

Additional help was provided by the following:

Original Design:		
   Jennifer Hook

Music composed and performed by:		
   Ian Livingstone (http://www.mediathemes.co.uk)

Special Thanks:
   "Katravax"
   Ben Hines
   Tom Hubina
   Mike Kulas
   Peter Lincroft
   Cara McDermott
   Jim McNally
   Casey Muratori
   Jeff Roberts
   Lorene Shaw
   Luc van den Borre
   Ramona and Donnie Young
   our many other friends and families for their
      support, advice, feedback and encouragement!

********************
* VII. Legal Stuff *
********************

=== Copyright ===

Candy Cruncher (C) 2001 Pyrogon, Inc.
All other copyrights and trademarks are property of their respective
owners.  All rights reserved.

=== Ogg Vorbis ===

Candy Cruncher uses the Ogg Vorbis codec for streaming audio from
Xiphophorous, licensed under the following terms:

"Copyright (c) 2001, Xiphophorus

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

- Redistributions of source code must retain the above copyright
notice, this list of conditions and the following disclaimer.

- Redistributions in binary form must reproduce the above copyright
notice, this list of conditions and the following disclaimer in the
documentation and/or other materials provided with the distribution.

- Neither the name of the Xiphophorus nor the names of its contributors
may be used to endorse or promote products derived from this software
without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE REGENTS OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE."

*************************
* VIII. VERSION HISTORY *
*************************
1.17
- calling RestoreDisplayMode() explicitly when shutting down DD
- no longer draw Buy Now when paused for RA build

1.16
- cleaned up key handling support
- Win32 version now derives archive file from path name

1.15.RC0
- you can now quit with Cmd-Q or Alt-f4 when paused
- start level bonus is now printed

1.15.B00
- first Mac OS X version!
- removed "for Windows" bit from the exit screen
- fixed some Apple UI consistency bugs (e.g. not supporting Cmd-Q, Quit event 
  from Dock)

1.12.xx (internal only)
- bonus for starting at later levels! (6/25K, 10/75K, 14/150K, 18/300K, 22/500K)
- RA support
- automatically paused when losing focus, however no longer
  unpauses when focus is regained
- bounce sounds no longer overlap

1.11.B00 (internal only)
- when counting down time bonus, licorice no longer blinks
- converted all BMPs to 16-bit TGAs
- implemented HGDI2DDisplayDevice and blitter
- removed DirectDraw support
- streaming audio now implemented without notifications
- changed compiler detection conditionals
- event record/playback implemented
- reduced CPU utilization when paused
- removed splash screens for smaller download and faster
  startup times
- demand load some assets to speed up load times
- implemented Mac/Carbon version
- changed icon display behaviour
- removed a lot of state machine ugliness and replaced
  with modal dialog handlers
- added PGxxxx sub-framework for UI items
- frame rate counter added
- game over is shown before taking you to high scores
- options don't restart the game in full version
- minor aesthetic changes
- now says "fullscreen on/off" instead of "windowed/fullscreen"
- hardcoded clear color support

1.10.RC3
- DEMO ONLY: fixed several bugs related to the demo, specifically
	* game would pause (instead of auto-unpausing) doing a Restart
	* game could get in an infinite loop with the "Full version only"
	  dialog boxes if you clicked on multiple items while the
	  dialog box was active.
- fixed up some of the control paths

1.10.RC2

- release candidate

1.10.x

*** ALL BUILDS ***

- bonus for remaining time when a level is completed!
- fixed privileges problem where we were creating keys
  in HKEY_LOCAL_MACHINE.  This caused problems for users
  on NT, XP or Win2K who did not have privileges to 
  modify those registry entries.  Adjusted now so that
  if we can't access HKLM we attempt to use
  HKEY_CURRENT_USER
- floater scores no longer inadvertently "linger"
- converted tile animations to JPEG
- converted most sound effects to Ogg Vorbis
- added animation for exploding black jellybean
- added sounds for candy cane introduction, black jellybean
  destruction, level up and one more to go
- new registry interface subsystem, including attempts to
  write to HKEY_CURRENT_USER when HKEY_LOCAL_MACHINE fails
- all options are now saved and reloaded
- sound plays when clicking on menu options
- new options dialog which now allows you to specify sound and
  music enabled/disabled separately; choice of starting level (full
  version only); alarm sound can be disabled; and you can now
  configure the arrow keys to "move space" or "move candy".
- restart button
- level entry in the high scores area expanded to 3 digits
- time for each level is now specified per level instead of globally
- added a loading progress bar
- fixed bug where if we failed to get a notification object
  the game would crash instead of just disabling music.  This is 
  only an issue on VERY old sound cards with VERY old drivers.
- added hint page about sliding the space and reduced time
- added distribution partner conditionals and assets
- made first two levels last MUCH longer
- (debug only) level warp now unbounded
- switched to external PYZ files

*** DEMO VERSION ***
- added a reverse progress bar for exit screen

*** FULL VERSION ***
- clicking on the game area will unpause a paused game
- choice of start level in options menu

1.05.4
- added commas to numbers

1.05.3
- fixed minor bug with keyboard handling after Game Over

1.05.2 (DEMO VERSION ONLY)
- fixed minor bug with pink "peek through" for "Maybe Later" icon

1.05.1
- fixed minor bug where hitting enter after the High Scores screen would
  cause the game to immediately start instead of taking the player to
  the info start screen
1.05
- first official release
- fixed show stopper bug where blank would disappear due to race condition
- "declick" the mouse when losing focus or going to fullscreen

1.04
- fixed bug with click/drag support
- added keyboard support

1.03
- minor aesthetic changes
- click/drag support!
- tweaking game balance

1.02
- fixed typos in some messages
- demo is now limited to playing 50 times

1.01 
- added "floater" scores

1.00 
- first internal release candidate

