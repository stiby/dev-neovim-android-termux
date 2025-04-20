# Dev neovim android termux

## Purpose

Setting myself the challange to do some development on my Samsung Tablet, using
the DEX desktop environment. This provides me with a portable development 
environment and with the DEX mode available on Samsung phones provides options
to do some work without even having a laptop to hand.

Having done some looking around there isn't any very mature local development
environments on Android, there are some text editors but to get a really 
productive environment I looked else where and VIM/Emacs options were 
considered.

Given I've only been an amature in VI for decades and knowing the editor in 
the right hands can be very productive this was also an option to learn that
as well.

I followed ThePrimagen's video 
https://youtu.be/w7i4amO_zaE?si=XoRADC9qvzrcchZO setting up an environment from
scratch and making a few tweaks for the langauges I was interested in, being
node.js (with type script support) and go lang.

This environment using the tmux tool to split the workspace up allows me to 
write code, running a watch command which runs the test suite on save, allowing 
me to consistently ensure my code base is in a working state between commits.

## Capabilities

Using this environment for a couple of weeks I have found it very capable for 
writting go application, I have even been building a UI but have hit a blocker
on the web debug, the android browsers don't have the debug tools/jconsole you
would get with the desktop equivilants.

## The future

With Android 15 having linux terminal from a virtual linux machine running on 
the device gives hope that the desktop options for android just need a way of 
running desktop applications, even sand boxed in a container to provide app
isolation could turn Android phones/tablets into real laptop replacement, we
will need more RAM and with ARM CPUs being very capabale.

