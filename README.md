# mafu's Cydia Repository

## Package debs
```sh
apt-ftparchive packages ./debs > Packages
bzip2 -kf Packages
gzip -c Packages > Packages.gz
```