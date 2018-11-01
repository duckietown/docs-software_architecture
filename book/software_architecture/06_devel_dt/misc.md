
## Downloading resources

Use this recipe if you need to download things:

    from duckietown_utils.download import download_if_not_exist
    url = 'https://www.dropbox.com/s/bzezpw8ivlfu4b0/frame0002.jpg?dl=0'
    f = 'local.jpg'
    download_if_not_exist(url, f)

(Do not commit JPGs and other binary data to the `Software` repository.)

TODO: actually use `urls.yaml`
