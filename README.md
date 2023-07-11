# disable-disable-devtool

Some of you might have found some websites that aggressively block devtools from being used, even going back one page to unload the website.

One of these tools that some websites use is [theajack/disable-devtool](https://github.com/theajack/disable-devtool).

I made this repository to call out these horrendous tools that try to limit what the user is allowed to do.

## How to block `disable-devtool`

I personally use [uBlock](https://ublockorigin.com/) since it's widely-used and easy, but you should be able to use this with any extension that can limit scripts from being loaded.

1. In uBlock, there is a button to log the requests of a webpage. Click this and refresh the page.

![image](https://github.com/dark-swordsman/disable-disable-devtool/assets/7909209/4c7c9920-8b79-4a1f-9b89-66aa6b32e920)

2. Search for "devtool" and you might see something like `cdn.jsdelivr.net/npm/disable-devtool`. Click on this entry, go to "static filter", and you can create a filter to block this script.

![image](https://github.com/dark-swordsman/disable-disable-devtool/assets/7909209/b5f0d614-80d5-4e32-9d17-aa18be53920e)

3. Refresh the page aftear creating, and enjoy limitless devtools!
