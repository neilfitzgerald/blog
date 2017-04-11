---
title: Going Round the World
tags:
  - On Testing
  - Testing
  - Process
  - On Process
  - Internationalization
  - Localization
date: 2017-04-11 09:05:54
---

Internationalizing your website or application is both easy, and hard. At the basic level it's substituting in different strings and resources based on locale, but it gets much more complicated quickly.<!-- more -->

For example, an application I was dealing with was re-using many of its language keys. It turned out that verb tense in a page header needed to be different then in a dialog in russian. In english and many other languages the you could use the same phrase in both places. This example shows you can’t just assume that a direct translation can always be used in multiple places.

In another instance a website used a completely different design and authentic in Japan to gain significantly more traffic vs. the standard design used in other countries. In another case involving Japan, an issue for a website was only showing up when run on the localized version of the operating system.

In all localized applications or websites I’ve dealt with length of text was an issue. It's common for a design that looks fine in english, but to have words overflow, or wrap in odd ways in other languages. This also impact the limits for data entry elements in the user interface. Usually you want to make sure the limit is high enough that it can accommodate locale specific needs. 

Most languages are left to right languages. In these languages, things are scanned from the top left down to the right. Right to left languages and cultures like hebrew and arabic, are scanned from the top right and down to the left, requiring moving many user interface elements to truly localize. To add to the complication, you may have items that are left to right, embedded inside a right to left language. In a case I was involved with, we had to talk to someone who spoke and wrote the language to understand how it should behave.

Choices of colors, icons, and imagery can be impacted by locale. A particularly sensitive example for symbols is the swastika. In many countries it is a stigmatized symbol due to its association with Nazism. In India, where the symbol first appeared thousands of years ago, it is a sacred religious symbol. 

Many of the technologies used today take care of the multi-byte nature of many languages. If something is being developed in a more low level language like C++, this may become more of a factor to look into.

Make sure you have a good process in place to get things translated. There is a need to factor in turnaround time, especially if you are using contract translators. With a good process, and proper review of your locale specific changes, your users around the world will have better experiences and your business better results.

## Key Points
* Keep a lookout for items in the default language (usually english) when looking at other locales.
* Use different keys for each location text appears.
* Look at the user interface in the most highly verbose languages.
  * Usually Germanic or Nordic languages have the longest words. Norwegian can be longer than German.
* Make sure colors are reviewed by a local. Colors can carry different associations depending on locale.
* Make sure images, icons, and messaging are reviewed by a local. Some maybe offensive, or not carry the intended message for a locale.

## Resources
* [Lorem Ipsum](http://www.lipsum.com/). (n.d.)
* [Cultural blunders: Brands gone wrong](http://www.campaignasia.com/article/cultural-blunders-brands-gone-wrong/426043 ). Mike Fromowitz. (October 7, 2013) In Campaign. 
* [Brand blunder](https://en.wikipedia.org/wiki/Brand_blunder) (n.d.) In Wikipidia.
* [Colours and Their Meanings in Different Cultures Around the World](https://www.triphobo.com/blog/significance-of-colors-in-various-cultures). Neha Kapoor. (Febuary 17, 2016). In TripHobo. 
* [Swastika](http://en.wikipedia.org/wiki/Swastika). (n.d.) In Wikipedia.