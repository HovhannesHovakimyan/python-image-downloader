# Web Image Downloader using Python
Python script which downloads images from given URL

# Initial setup:
- `pip3 install -r requirements.txt`
- 
    ```
    python download_images.py --help
    ```
    **Output:**
    ```
    usage: download_images.py [-h] [-p PATH] url

    This script downloads all images from a web page

    positional arguments:
    url                   The URL of the web page you want to download images

    optional arguments:
    -h, --help            show this help message and exit
    -p PATH, --path PATH  The Directory you want to store your images, default
                            is the domain of URL passed
    ```
- Example command to download all images from https://jzechner.com
    ```
    python download_images.py https://jzechner.com
    ```
    A new folder `jzechner.com` will be created automatically that contains all the images of that web page.