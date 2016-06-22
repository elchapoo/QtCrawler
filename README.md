# QtCrawler
Script to automatically visit female profiles on interpals

# Breaking news: 21 - June - 2016
Interpals starts throttline the amount of possible views. Inside the throttle branch you can find a first implementation of a throttle, which represents a try to avoid the block. Although, this doesn't seem to work. 

If anyone is interested in working with me on solving the issue, join #qtcrawler on Freenode.
Throttle implementation for online page only (deactivated jumper to next page, breaks UI):
https://github.com/DccrsD/QtCrawler/blob/throttle/qtcrawler.user.js

## Release information

Beta version for testing. Currently only tested in Chrome. 

## Usage

1. Download tampermonkey and install as userscript.
2. Login to interpals
3. go to "Online"
4. set your filters
5. scroll down and click on "View all on one page"
6. click on "view all profiles"


## New

Added functionality to send message to all users. Just click "message all". It won't message users you've already talked to.

