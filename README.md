# Web Image Downloader using Python
Python script which downloads images from given URL

# Initial setup:
- You need to have Python and PIP installed
- `pip3 install --upgrade pip`
- `pip3 install -r requirements.txt`
- 
    ```
    python3 img-down.py --help
    ```
    **Output:**
    ```
    usage: img-down.py [-h] [-p PATH] url

    This script downloads all images from a web page

    positional arguments:
    url                   The URL of the web page you want to download images

    optional arguments:
    -h, --help            show this help message and exit
    -p PATH, --path PATH  The Directory you want to store your images, default
                            is the domain of URL passed
    ```
- Example command to download all images from https://ajapnyakmc.com
    ```
    python3 img-down.py https://ajapnyakmc.com
    ```
    A new folder `ajapnyakmc.com` will be created automatically that contains all the images of that web page.