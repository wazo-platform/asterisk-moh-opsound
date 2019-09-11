asterisk-moh-opsound
====================

asterisk extra sound files (MOH)

Dependencies
============

run the following command to install depedencies:

    apt-get install devscripts

Build package
=============

To download sources and build package, execute:

    ./debian/rules get-orig-source
    tar xf asterisk-moh-opsound_2.03.orig.tar.gz
    cp -r asterisk-moh-opsound-2.03/* .
    debuild -us -uc

The packages will be placed in the parent directory (```cd ..```)
