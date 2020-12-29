# altpwr.net
The old altpwr.net website was hosted on wordpress.com and seems to be lost to history. Luckily, most bits got scraped by the internet archive, so here's a try to to mirror it.

## How
I used https://github.com/hartator/wayback-machine-downloader (docker version) to mirror the page off of webarchive.

```
docker run --rm -it -v $PWD/websites:/websites hartator/wayback-machine-downloader -t 20171231 https://www.altpwr.net/
```

There were many broken links, so I had to do some manual adjustments.

## Original base
https://web.archive.org/web/20171204032204/https://www.altpwr.net/
