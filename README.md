From [rclone.org](http://rclone.org):

Rclone is a command line program to sync files and directories to and from

  * Google Drive
  * Amazon S3
  * Openstack Swift / Rackspace cloud files / Memset Memstore
  * Dropbox
  * Google Cloud Storage
  * Amazon Cloud Drive
  * Microsoft One Drive
  * Hubic
  * Backblaze B2
  * Yandex Disk
  * The local filesystem


## Docker

Run it (displays version info):

```bash
/usr/bin/docker run --rm kjvellajr/rclone
```

Interactive configuration:

```bash
mkdir config
/usr/bin/docker run --rm -it -v "$PWD"/config:/config kjvellajr/rclone config
```
