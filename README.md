## GoSignify

Forked & Reworked from https://github.com/frankbraun/gosignify

> gosignify is a Go reimplementation of OpenBSD's signify

([manpage](http://www.openbsd.org/cgi-bin/man.cgi/OpenBSD-current/man1/signify.1), [CVS](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/signify/)).

It strives to be fully compatible with the original C implementation

    $ go get -v github.com/FolowMeDown/gosignify
    $ make update-vendor
    $ make

USAGE :
./GoSignify -G -p public.key -s private.key
