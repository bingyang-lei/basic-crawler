# basic-crawler
## Two ways for crawling dynamic web page——taking Chinese stock market as an example.
As we know, the typical way for crawling web page is using request and bs4 packets in python. However this way is only useful for static web pages, but nowadays, most web pages are using javascript to show information, this is dynamic so request is no longer applicable.
The two ways for crawling dynamic web page is manually locate dynamic requests(mainly .js file) and use selenum lib.The stock.ipynb flie using the first way, and the selenum.ipynb using the second way.

