# Gentoo / Funtoo Portage overlay

## What

An overlay for the Portage tree, targeting Gentoo and Funtoo Linux, containing
ebuilds, authored by yours truly.

For more info, see:
https://wiki.gentoo.org/wiki/Overlay

## Why

Sometimes I'm looking to do one or more of the following:
	* Install a program not presently in the Portage tree
	* Install a different version than what's presently in the official Gentoo
	or Funtoo portage trees
	* Enable or experiment with features in the program that the current
	official build doesn't use
	* Fix bugs in an ebuild
	* Alter how an ebuild manages the installation of a program to better suit
	my needs & wants

This repo is a place for me to do the above without having to worry about my
changes getting overwritten when I sync the main offical Porage tree.

## Misc

### Stability
Generally, the goal is to have ebuilds that actually build and install packages
correctly without borking the rest of the system, and ebuilds in the master
branch should remain in that state so long as they have not been obsoleted by
newer versions in the offical Gentoo or Funtoo portage trees.

Any ebuilds in any other branches are in no way garaunteed to resemble anything
even resembling usability, much less stability, at any time. Use them at your
own risk.
