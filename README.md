# vpnGUI
This a node.js frontend for WireGuard

Extract the tar.bz2 file in the directory of your choice and make sure that
you install pug and express before running it.

The port where it listens, default 8000, can be changed in index.js or by
creating an environment variable NODE_PORT and assigning it the value of your
choice.

In the same manner you can change the folder where the WireGuard profiles are
stored. Either change it in index.js or by creating an environment variable,
PROF_FOLDER, the default is /home/pi/config (as you can imagine I run it on a
RPi)

# License
Copyright (c) 2023 Jose J. Cintron - l0rddarkf0rce@yahoo.com

This program is free software; you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the
Free Software Foundation; either version 3 of the License, or (at your
option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for
more details.

You should have received a copy of the GNU General Public License along
with this program; if not, see <https://www.gnu.org/licenses/>
