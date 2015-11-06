# Hardware #

If you want to install a multiseat system with Multiseat-wizard-bicefalo, you need a video card with two or more outputs. Nowadays new computers have got these video cards.

Multiseat-wizard-bicefalo uses Xephyr, then a single video card is needed.

![http://multiseat-wizard-bicefalo.googlecode.com/svn/wiki/images/Conectores.jpg](http://multiseat-wizard-bicefalo.googlecode.com/svn/wiki/images/Conectores.jpg)

Your video card could contain 3 types of outputs:
  * VGA
  * HDMI
  * DVI
Usually your video card has got VGA output, you will need two monitors, a monitor with HDMI or DVI inputs and another one with VGA input.

You can buy a DVI to VGA connector:

![http://multiseat-wizard-bicefalo.googlecode.com/svn/wiki/images/DVItoVGA.jpg](http://multiseat-wizard-bicefalo.googlecode.com/svn/wiki/images/DVItoVGA.jpg)

Be careful with HDMI to VGA connector:

![http://multiseat-wizard-bicefalo.googlecode.com/svn/wiki/images/cablevgahdmi.jpg](http://multiseat-wizard-bicefalo.googlecode.com/svn/wiki/images/cablevgahdmi.jpg)

HDMI is digital connection. VGA is analogic connection. Last wire doesn't work. This kind of wire is only for special devices.

**Note:** Your video card could contain three outputs, but only two could work. Please read your video card manual.

# Linux drivers #

Multiseat-wizard-bicefalo only works with free software drivers.

Privative drivers change xrand program behaviour. xrand is needed in order to configure screen resolution. Privative drivers don't usually work with  xrand.

# A simple test #

Does my computer work ok with multiseat?

There is a very simple test. Run in your computer several sessions of programs that you are going to use in your multiseat system. You must run so programs as seats you are going to set up. If it works, multiseat will work in your system.

If your CPU has got two or more cores, it will work better in multiseat.