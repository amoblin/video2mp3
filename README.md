# Requirement

- mkvtoolnix
- mkvinfo
- mkvextract
- id3v2

# Install

    $ wget http://downloads.sourceforge.net/project/id3lib/id3lib/3.8.3/id3lib-3.8.3.tar.gz
    $ tar zxvf id3lib-3.8.3.tar.gz
    $ cd id3lib-3.8.3
    $ patch -p1 < patch
    $ ./configure --prefix=/usr/local/Cellar/id3lib/3.8.3
    $ make && make install
    $ brew link --overwrite id3lib
    $ brew install id3v2
