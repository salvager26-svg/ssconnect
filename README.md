![ssconnect: ShipStation Connect for Linux](banner.png)

# ssconnect: ShipStation Connect for Linux

ShipStation has no Connect app for Linux. ssconnect is one that works.

Click **Print** on the ShipStation website and the label prints on the printer plugged into your Linux computer. It was built for a Zebra 4x6 thermal printer, and other printers that Linux can see work too. After install it keeps running in the background, so nobody has to stay logged in.

**Get it: [patreon.com/ssconnect](https://www.patreon.com/ssconnect)**

This is an independent project. It is not made by ShipStation, and ShipStation support cannot help with it.

## What it does

- Connects your Linux computer to ShipStation the same way the Windows Connect app does, so the computer and its printers show up in the ShipStation print box.
- Prints ZPL labels raw and PDF labels at 4x6.
- Small window that shows whether the computer is connected and which printers it sees. Closing the window leaves printing running.
- One AppImage file. No Windows, no virtual machine, no Wine.

## What it does not do

- It prints only. There is no scale support yet.
- It is for desktop Linux on a normal PC. Raspberry Pi (ARM) is not supported yet.
- It does not pick a default printer for you. You choose the printer in the ShipStation print box, the same as on Windows.

## Which Linux

Tested on an Arch-based desktop (KDE). It is built on Ubuntu 22.04 and is meant to run on that or anything newer. Other distros have not been tested yet. The 7-day trial is there so you can check yours. The computer needs CUPS, which most desktop Linux already has.

## How to get it

1. Join **Station** (1 computer, $12 a month, with a 7-day trial) or **Bench** (up to 3 computers, $29 a month) at [patreon.com/ssconnect](https://www.patreon.com/ssconnect).
2. Download the AppImage from the members post.
3. Open it, press **Sign in with Patreon**, then sign in with your ShipStation username and password. The password stays on your computer.
4. Print from ShipStation.

## Support

Email salvager26@gmail.com. Say which Linux you are on and which printer you picked.

## Why this exists

ShipStation's community has asked for Linux support for years: [ShipStation Connect - Linux Support](https://community.shipstation.com/ideas/shipstation-connect-linux-support-5194). Until they ship it, this is a way to stop running a Windows VM or a spare Windows PC just to print labels.
