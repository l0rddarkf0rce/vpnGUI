# vpnGUI
This a node.js frontend for WireGuard

ISC License (ISC)
Copyright 2021 prb0rg

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR
OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
PERFORMANCE OF THIS SOFTWARE.

Extract the tar.bz2 file in the directory of your choice and make sure that
you install pug and express before running it.

The port where it listens, default 8000, can be changed in index.js or by
creating an environment variable NODE_PORT and assigning it the value of your
choice.

In the same manner you can change the folder where the WireGuard profiles are
stored. Either change it in index.js or by creating an environment variable,
PROF_FOLDER, the default is /home/pi/config (as you can imagine I run it on a
RPi)
