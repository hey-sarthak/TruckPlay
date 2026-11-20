====================================================================
  TRUCKPLAY - your Euro Truck dashboard on an old tablet
====================================================================

TruckPlay shows the WestPlay truck dashboard from Euro Truck
Simulator 2 on your tablet, over your own Wi-Fi. You can tap and drag
on the tablet to use it, like a second screen for the truck.

Everything you need is in this one file: TruckPlay.exe. It can
install WestPlay for you if WestPlay is missing.

--------------------------------------------------------------------
  BEFORE YOU START
--------------------------------------------------------------------
 * Euro Truck Simulator 2 must be installed.
 * The tablet and the PC must be on the same Wi-Fi network.
 * The tablet needs Google Chrome (any recent browser works).
 * Windows 10 or Windows 11, 64-bit.

 WestPlay does not need to be installed beforehand: the TruckPlay
 setup window offers to download and install it from WestPlay's
 official GitHub page.

--------------------------------------------------------------------
  START TRUCKPLAY (4 steps)
--------------------------------------------------------------------
 1. Double-click TruckPlay.exe.

    If Windows shows a blue "Windows protected your PC" message,
    click "More info" and then "Run anyway". This appears because
    TruckPlay is a free app from a small project, not because it is
    dangerous.

 2. In the setup window, look at the WestPlay row.

    - "Not installed": click "Install". TruckPlay downloads the
      official WestPlay installer (about 12 MB) and runs it for
      you. Wait until the row says "Installed".

      First time only: open WestPlay once from the Start Menu, let
      its short setup find Euro Truck Simulator 2, then close it
      again. TruckPlay uses the files that setup installs.

    - "Installed": nothing to do; continue.

 3. If Windows asks whether TruckPlay may use the network, click
    "Allow access". TruckPlay also has an "Allow" button in its
    window if you missed it.

 4. Click "Start TruckPlay" and look at the TruckPlay window. It
    shows two things:
      - an address, for example  http://192.168.1.36:18733
      - a six-digit code, for example  280925

    Close the WestPlay app while TruckPlay runs, or let TruckPlay
    close it with one click.

--------------------------------------------------------------------
  CONNECT THE TABLET (one time)
--------------------------------------------------------------------
 1. On the tablet, open Google Chrome.
 2. Type the address exactly as shown in the TruckPlay window.
 3. Type the six-digit code.
 4. Tap "Connect".

The tablet remembers the connection. Next time you only need to open
TruckPlay and start driving.

Tip: use the 5 GHz Wi-Fi network if your router has one - video will
be smoother.

--------------------------------------------------------------------
  THE TRUCKPLAY WINDOW
--------------------------------------------------------------------
 "Ready"        everything is working; connect the tablet.
 "Starting"     wait a few seconds.
 "Needs setup"  read the message in the window and click the button
                next to it.
 "Install      downloads WestPlay from its official GitHub release
  WestPlay"    and installs it for you.
 "Preview on    opens the same screen in a browser on the PC, so you
  this PC"      can check it before picking up the tablet.
 Copy           copies the address or the code to the clipboard.

Closing the window does NOT stop TruckPlay: it keeps running in the
notification area (bottom-right of the screen). Click its icon to
open it again. To really stop it, click "Quit".

--------------------------------------------------------------------
  IF SOMETHING DOES NOT WORK
--------------------------------------------------------------------
 * The tablet cannot open the page
   - Check both devices are on the same Wi-Fi (not guest Wi-Fi).
   - Click "Allow access" in TruckPlay, or answer "Allow" when
     Windows asks about the network.
   - Click "Preview on this PC": if that works, the problem is the
     network between the tablet and the PC.

 * "Wrong code"
   - The code is the six digits shown in the TruckPlay window.

 * The tablet shows a black screen or "Waiting for the game"
   - Start Euro Truck Simulator 2 and get into a truck.
   - Some trucks have no compatible dashboard screen. That is a
     limitation of the game, not of TruckPlay.

 * Video is choppy
   - Move the tablet closer to the router, use 5 GHz Wi-Fi, or open
     Settings in TruckPlay and choose "Smooth".

 * TruckPlay says WestPlay is running
   - Close the WestPlay app while TruckPlay runs. TruckPlay offers a
     button that closes it for you.

 * WestPlay installation does not finish
   - Check the internet connection and click "Try again".
   - You can also install WestPlay yourself from
     https://github.com/enes-less/WestPlay/releases/latest and then
     reopen TruckPlay.

More help is in the TruckPlay window under "Help".

--------------------------------------------------------------------
  REMOVE TRUCKPLAY
--------------------------------------------------------------------
 Open TruckPlay, click "Settings", then "Remove TruckPlay". Your
 pairing settings are kept; WestPlay and the game are not touched.
 Afterwards you can delete TruckPlay.exe.

--------------------------------------------------------------------
  ABOUT
--------------------------------------------------------------------
 TruckPlay is free software, licence GPL-3.0-or-later, based on the
 WestPlay project. It does not modify WestPlay or Euro Truck
 Simulator 2.

 TruckPlay uses the internet only when you click "Install" to get
 WestPlay. It downloads only from WestPlay's official releases on
 GitHub and sends nothing else.

 Source code information: see SOURCE.txt.
