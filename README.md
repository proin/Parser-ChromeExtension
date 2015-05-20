# Clipper

Clipper is Chrome Extension which is extracting some values in active tab by css selector.

![alt tag](https://github.com/proin/Parser-ChromeExtension/blob/master/lib/example.png?raw=true)

## How to Install
1. download this repo. and unzip.
2. move to `chrome://extensions` and click load extension button.

- references: https://developer.chrome.com/extensions/getstarted

## How to Use
- example site: `http://www.aswc2006.org/accepted.php` (this site is conference site that contains some of academic data)
- move to example site and spider button in `Browser Action`
- input `.Section1 tr td:nth-child(1)` and click find button (this action do filtering paper's title by css selector)
- input `.Section1 tr td:nth-child(2)` and click find button (this action do filtering paper's author name by css selector)

## Search Parameters
- css selector (top input): find elements by css selector, basically each elements attribute(innerText) is printing application.
- remover (left input): remove elements in finded element.
- inner (center input): find elements in finded element.
- attr (right input): attribute to print applicatiion. text means innerText, other attributes like to basic css attributes (ex. href, title, etc).
