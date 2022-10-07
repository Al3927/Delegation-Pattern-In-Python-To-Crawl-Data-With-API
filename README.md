<p align="center">
  <br />
    <a title="banner" href="#"><img width="600px" src="img/banner.png" alt="banner" /></a>
  <br/>
</p>

> An effective way is widely used in the mobile development sector to build APIService, which I now bring to the data-related sector.

# Delegation Pattern In Python To Crawl Data With API

- [Delegation Pattern In Python To Crawl Data With API](#delegation-pattern-in-python-to-crawl-data-with-api)
  - [The problem it solved](#the-problem-it-solved)
  - [Knowledge Base](#knowledge-base)
    - [Catch that API call](#catch-that-api-call)
    - [Delegation Pattern](#delegation-pattern)
  - [Structure](#structure)
  - [Application](#application)
    - [Shopee](#shopee)
    - [Artstation](#artstation)
    - [Tinder](#tinder)
    - [Pexels](#pexels)

## The problem it solved

- Crawl data easily
- Collect any possible data you want, even Tinder! (check robots.txt to make sure you are not violent with any rules)
- Wide range use

## Knowledge Base

### Catch that API call

I have a demonstration in [this repo](https://github.com/comphilano/ds_final/blob/main/Slide.pdf) (Crawl data section).

### Delegation Pattern

## Structure

- APIService
- ItemModel
- GetData

## Application

### Shopee

 :loudspeaker: **Up-to-date: 07/10/2022**

 [How to use the crawler](https://github.com/comphilano/ds_final#crawler)

Go to the Shopee [folder](application/shopee).

### Artstation

Go to the Artstation [folder](application/artstation).

:bulb: TODO: This is the code from November 2021, now October 2022, for some reason, looks like it crawls all the data available with `per_page = 3, max_page=1`, so:

- Check the API call
- If you decide to use this code, make sure to check attribute `all_items` to not have any duplicate value, and limit it, because calling the method `crawlImage()` will take time.

### Tinder

Should I publish it 🤔

### Pexels

Go to the Pexels [folder](application/Pexels).

Not done yet! Now it works on a JSON file you already downloaded, use the function on `GetData`, need to change the APIService.
