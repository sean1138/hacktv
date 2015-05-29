# hacktv
Project for a friend that wants to replicate the look and feel of the old WebTV browser in their website.

The WebTV browser had a viewport of 640x480 - try to imagine that resolution on a 32 inch TV if you're too young to remember what it was like - it was pretty darn good at the time actually.  WebTV was a television set-top box that had just enough processing power to run a web browser in the mid to late 1990s - 8MB of RAM, 1GB hard drive, 150MHz processor.  It was the cheapest way to get on the internet at the time with the boxes retailing for less than $300 if my memory is accurate.  I owned a Philips WebTV Plus unit that added the ability to capture still images from video inputs as well as features more focused on TV viewing than internet browsing.  The internet access fees were, of course, monthly just like any other ISP and you could also use an ISP that was independant of WebTV or MSNTV.  Microsoft purchased WebTV in 1997.  You can check out wikipedia if you want to know more http://en.wikipedia.org/wiki/MSN_TV

## Recreating the WebTV browsing experience
Since I can find video of it it's easier to watch to get an idea of how the WebTV browser worked than try to explain it.
https://youtu.be/yuvDkIZmU3s?t=3m16s

There was no mouse or other pointer device on WebTV, it was all keyboard navigation via the arrow keys or buttons on a remote control.  Desktop browsers can navigate links via the tab key and it was decided that this functionality was good enough rather than using a script for navigating with the arrow keys exactly the way that it worked in the WebTV browser.

template.html is the example produced for the client to use and learn how to write modern html from and was intended to be the src of an iframe in a different html file.

template2.html includes the frame of the website and the content in one file.

There were no scrollbars in the WebTV browser, that's what the arrows at the bottom right are for, scroll indicators.  Since he uses firefox he doesn't care about other browsers and these arrows do not work in IE10.  IE11 was not tested but they probably don't work there either.

The animated green heartbeat graph next to the scroll indicator arrows was used to show when there was network activity (downloading) on WebTV.  In this project it's just a looping animation.

index0 and index4 are an earlier version, index4 is the src of an iframe in index0.

The original html can be seen at http://turdinc.kicks-ass.net/Msntv/index2.html
