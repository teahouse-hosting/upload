# Teahouse Upload
This does the standard configure and sync needed to update a website from build artifacts.

This takes two inputs:
* `domain`: The domain name of the website to update
* `root`: The name of the directory to sync with Teahouse (ie, your build directory)

It will delete missing files.

If you don't like the defaults provided by this, you can use [`configure-s3`](https://github.com/teahouse-hosting/configure-s3) and your own S3 client.
