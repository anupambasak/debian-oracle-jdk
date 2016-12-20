Deb Packaging for Oracle JDK

Place oracle JDK in debian-oracle-jdk/opt then run this command to build DEB package. Also change package Version in the DEBIAN/control as per JDK version.

dpkg-deb -b debian-oracle-jdk jdk1.8.0_112.deb
