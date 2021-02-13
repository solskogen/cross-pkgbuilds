To build these packages you MUST provide a TARGET variable to makepkg like so:
TARGET=s390x makepkg

build order is binutils -> linux-api-headers -> gcc-bootstrap -> glibc -> gcc -> glibc (again)
