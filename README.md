Ubuntu Kernel - Surface Pro 3
=============================

# apply patches using
patch -p1 --ignore-whitespace -i {patch}

# build using
DEB_BUILD_OPTIONS=parallel=4 AUTOBUILD=1 NOEXTRAS=1 fakeroot debian/rules binary-generic