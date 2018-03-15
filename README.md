
information_source: **IMPORTANT: This repository is used for class [PV204 Security Technologies at Masaryk University](https://is.muni.cz/auth/predmety/predmet?lang=en;setlang=en;pvysl=3141746). All meaningful improvements will be attempted to be pushed to upstream repository in June 2018.**

== YubiKey NEO App: OpenPGP - BUILD

[![Build Status](https://travis-ci.org/JavaCardSpot-dev/ykneo-openpgp-build.svg?branch=master)](https://travis-ci.org/JavaCardSpot-dev/ykneo-openpgp-build)

This project implement the OpenPGP card functionality used on the
YubiKey NEO device that is sold by Yubico.

This project is based on the 
https://github.com/jderuiter/javacard-openpgpcard[Java Card OpenPGP Card]
project made by Joeri de Ruiter. 
The initial modifications we have made compared to
the upstream project are minor, but we reserve the right to make other
changes and improvements that are specific to the YubiKey NEO
hardware.

=== License

The upstream project was released under the GPLv2+ and our fork uses
the same license.  All of our changes are released under the same
license.  See the file LICENSE for more information.


=== Building

See doc/Building.txt for information on how to build the source code
and doc/InstallCAPFile.txt on how to install it.


=== Usage

The OpenPGP Card applet is typically used through http://www.gnupg.org[GnuPG]
so we refer to its documentation for the full reference.

The default PIN set is `123456' and the default admin PIN is `12345678'

We have tutorials on specific topics in at
https://developers.yubico.com/PGP[developers.yubico.com/PGP], for example card
editing and key import.
