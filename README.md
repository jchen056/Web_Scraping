# Web_Scraping
A project done for The Grove School of Engineering to measure how CUNY provides students with a pathway to economic mobility.

## Basic Web Scraping
* physical layer(actual electrons on a wire)
* data link: frames MAC addresses and physical machines on a local network
* network: router to router, creates network IP addresses, variable-length packets
* transport: persistent communication channels, TCP, UDP, ports
* session: open, close, manage sessions
* presentation: string encoding, encryption/decryption, object serialization, files, compression
* application: HTTP, POST


[link]https://www.linkedin.com/learning/web-scraping-with-python/what-is-web-scraping?autoSkip=true&autoplay=true&resume=false

**some definitions**:
1. web scraping: scrape data from a single web page; a program that requets and parses data on the web, esp in an unexpected way
1. web crawling: the act of moving from page to page
1. bots

## libraries and modules
1. selenium: interact with the wbe browser; 
>pip install selenium
>please note that selenium needs a driver to interface with the chosen browser
2. chromedriver: for selenium to interact with
3. beautifulsoup4: extract the content of a website
4. time: to delay an action by an amount of time
5. csv: to work with csv file

## test automation
1. unit tests
1. service/API layer tests
1. user interface tests: selenium

## HTML and DOM
we can locate HTML elements by:
* id attribute(unique)
