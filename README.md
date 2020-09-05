# python-downloader
Very shitty threaded downloader made in python with requests.

```
from downloader import HTTPDownloader

downloader = HTTPDownloader('https://upload.wikimedia.org/wikipedia/commons/5/58/Gustav_Vasa.jpg','./Vasa.jpg')
downloader.download()
```
