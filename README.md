#Deb Packaging for Oracle JDK

Place oracle JDK in debian-oracle-jdk/opt then run this command to build ***.deb*** package. Also change package Version in the DEBIAN/control as per JDK version.

You can direlectly check the [releases](https://github.com/basakanupam/debian-oracle-jdk/releases) for deb packages

```shell
dpkg-deb -b debian-oracle-jdk jdk1.8.0_112.deb
```
