# foxnews-scraper

A very simple shell script for scraping foxnews in json.

## Requirements

 - [reliq](https://github.com/TUVIMEN/reliq)
 - [jq](https://github.com/stedolan/jq)
 - parallel (not mandatory)

## Installation
    
    install -m 755 foxnews-scraper /usr/bin

## Json format

Here's [json](example.json).

## Usage

Script downloads all articles using sitemap.xml and writes it into stdout.

If you want to download it in parallel just uncomment the 3 comments and comment the for loop.
