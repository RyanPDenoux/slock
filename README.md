

# slock - simple screen locker

simple screen locker utility for X.


# Changes

This is my personal fork of `slock` but it should be instantly usable on any Arch based system.


# Patches

-   [CapsColor](https://tools.suckless.org/slock/patches/capscolor/)
-   [Xresources](https://tools.suckless.org/slock/patches/xresources/)
-   [Blur Pixelated Screen](https://tools.suckless.org/slock/patches/blur-pixelated-screen/)


# Requirements

In order to build slock you need the Xlib header files.


# Installation

Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


# Running slock

Simply invoke the &rsquo;slock&rsquo; command. To get out of it, enter your password.

