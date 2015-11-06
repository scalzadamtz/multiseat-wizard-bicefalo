# Introduction #

This is a simple wizard to install multiseat systems. A multiseat refers to multiple users using one personal computer, each with their own console, consisting of a keyboard, a mouse and a monitor.

You can see an example of multiseat here:

http://en.wikipedia.org/wiki/Multiseat_configuration

This wizard lets you to configure:

  * Screens resolution
  * Keyboard and mouse per seat
  * USB ports per seat

It uses Xephyr in order to get multiseat. Then it is focused to one video card with two or more outputs. See Hardware wiki:

http://code.google.com/p/multiseat-wizard-bicefalo/wiki/Hardware


# Install #

  * Install Ubuntu in your computer. Ubuntu, neither Kubuntu nor Lubuntu.
  * Download this wizard from http://code.google.com/p/multiseat-wizard-bicefalo/downloads/list
  * Connect your hardware, screens, keyboards and mices. Reboot your computer.
  * Then run this asistant from your terminal:

`sudo python main.py`

  * Follow asistant:

![http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo.png](http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo.png)

Assistant should detect number of screens (seats) connected:

![http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo-1.png](http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo-1.png)

Select resolution of each screen:

![http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo-2.png](http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo-2.png)

Select keyboard and mouse for each seat. Suggestion, press next:

![http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo-3.png](http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo-3.png)

Connect a pendrive in each USB port (or same pendrive several times) and press refresh. Select a seat and use add to add this USB port to this seat:

![http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo-4.png](http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/Pantallazo-4.png)

![http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/usb-ports.png](http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/usb-ports.png)

  * Then press apply and reboot your computer.
  * There is a new user multiseat, select multiseat user, password multiseat. Select Multiseat session:

![http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/login-multiseat-marcado.jpg](http://multiseat-wizard-bicefalo.googlecode.com/svn/trunk/trunk/manual/images/login-multiseat-marcado.jpg)

  * Multiseat will start, be patience.
  * User seat1, password seat1. User seat2, password seat2...
  * That's all.

In order to shut down a multiseat computer. Close all seats sessions and press physical power off buttom (only one click). Computer will shut down normally.