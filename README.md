# My build of suckless's dmenu

This build includes some patches (Mentioned below)

## dmenu - dynamic menu

dmenu is an efficient dynamic menu for X.


### Requirements

In order to build dmenu you need the Xlib header files.


### Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

```make clean install```


### Running dmenu

See the man page for details.

## Patches credits

- [center](https://tools.suckless.org/dmenu/patches/center/)
	- Ed van Bruggen edvb@uw.edu
  - Nihal Jere nihal@nihaljere.xyz (20200111)
- [border](https://tools.suckless.org/dmenu/patches/border/)
	- Leon Plickat - leonhenrik.plickat[at]stud.uni-goettingen.de
- [mouse support](https://tools.suckless.org/dmenu/patches/mouse-support/)
	- Hiltjo Posthuma - hiltjo@codemadness.org
	- Xarchus (for multisel support).
  - prx (for selectbg color on hovered item)
- [password](https://tools.suckless.org/dmenu/patches/password/)
  - Philip K. - philipk (at) posteo (dot) net
  - Mehrad Mahmoudian - m.mahmoudian Gmail (dmenu-password-5.0.diff)
