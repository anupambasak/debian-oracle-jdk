Deb Packaging for Oracle JDK

Place oracle JDK in opt then change to debian-oracle-jdk(outside the git repo) directory and run this command to build DEB package. Also change package Version in the DEBIAN/control.

dpkg-deb -b debian-oracle-jdk jdk1.8.0_112.deb
