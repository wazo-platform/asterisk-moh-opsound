## asterisk-moh-opsound

asterisk extra sound files (MOH)

# Dependencies

run the following command to install depedencies:

```shell
apt-get install devscripts
```

## Build Package

To download sources and build package, execute:

```
debian/rules get-orig-source
tar -xvf ../asterisk-moh-opsound_*.orig.tar.gz  --strip 1
dpkg-buildpackage -us -uc
```

The `.deb` will be located in the parent directory.
