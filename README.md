rpm-jansson
===========

An RPM spec file build and install the Jansson JSON C library

To Build:

`sudo yum -y install rpmdevtools && rpmdev-setuptree`

`wget https://raw.github.com/nmilford/rpm-jansson/master/jansson.spec -O ~/rpmbuild/SPECS/jansson.spec`

`wget http://www.digip.org/jansson/releases/jansson-2.4.tar.gz -O ~/rpmbuild/SOURCES/jansson-2.4.tar.gz`

`rpmbuild -bb ~/rpmbuild/SPECS/jansson.spec`