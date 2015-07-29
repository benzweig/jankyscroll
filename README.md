http://zweig.co/jankyscroll/

# jankyscroll.js 2.0

##### A Javascript scrolling plugin that doesn't need to exist.




## [<span class="octicon octicon-link"></span>](#welcome-to-github-pages)Welcome to **jankyscroll**

Jankyscroll makes your website's UX undeniably worse. Let's talk about a couple ways you could delude yourself into thinking that you want this.

1.  First and foremost, **jankyscroll** is a tool for randomized, organic content discovery. Users can unintentionally (and forcibly!) discover parts of your website they didn't know or care about, and probably still won't. Maybe that's something you want. I don't know.

2.  In today's diverse ecosystem, it can be a real challenge to support every available platform. Solutions like [Modernizr](http://modernizr.com/) do their best to help you adapt to all manner of devices, but **jankyscroll** elegantly resolves all issues. Performance will be just as terrible on a brand new, state-of-the-art machine as it was on your dad's old Compaq that caught fire that one time.

3.  For too long, content providers have allowed ungrateful _users_ to scroll wherever they please, whenever they please. With **jankyscroll**, you can assert your rightful dominance as a Provider of Value, and stop those thankless users from scrolling so freely. Control the Scroll, with **jankyscroll**. It sucks.

## [<span class="octicon octicon-link"></span>](#how-to)How to use **jankyscroll**

If you really want to use **jankyscroll**, I guess I can't stop you. First, you would include it in your page, like this. You should already know this stuff, probably.

    <script src="your/path/to/jankyscroll.js"></script>

Then, initialize the plugin at the bottom of your document, if you're a good programmer who follows best practices. Which you're obviously not, because you're still here, reading this garbage.

    jankyscroll(trigger_distance, jank_amount);

_trigger_distance_ sets the distance, in pixels, that one has to scroll before they get jank'd. _jank_amount_ sets an approximate range of just how jank'd they'll be, also in pixels.

    jankyscroll(400, 50);

For instance, the above code would mean that the user would be jank'd around by about 50px for every 400px scrolled.

Thankfully, that's all. If your _jank_amount_ is greater than your _trigger_distance_, that might cause some problems. Who cares.

### [<span class="octicon octicon-link"></span>](#jankyscroll-20)jankyscroll **2.0**

In order to bring users the most emergent janking experience, we've upgraded jankyscroll to version 2.0. This means we've added a third argument, `jank_method`, specifying the specific flavor of janking. There are three provided options:

* `"scroll"` (default) - Are you satisfied with the old jank? This is just that, the jank you know and love.
* `"offset"` - This is janking brought to the modern world. Instead of using obsolete shit to do shit, we're using CSS3, the best CSS since CSS2.
* `"hardcore"` - This option is for _hardcore_ jank junkies. Using advanced CSS3 technology, this will jank each element of the page separately.

    jankyscroll(400, 250, "hardcore");

There is also a fourth option, supplying a custom jank function. This function takes a integer value, `jank_amount`. This allows for _incredible_ jank extensibility. For example, sideways janking:

    jankyscroll(320, 160, function(jank_amount) {
        window.scrollBy(jank_amount, 0); // x, y
    });

## [<span class="octicon octicon-link"></span>](#support-or-contact)Support or Contact

Having trouble with **jankyscroll**? Sorry, I don't really know what to do about that. It's sort of trouble to begin with, no? I'm sure you'll figure it out.

If you'd like to contact me about **jankyscroll**: please, don't.

<del>It doesn't work on mobile, because I have homework to do tonight. If someone wants to pull request that, I'll probably laugh at you for wasting your time on this bullshit, but then accept it. So, you know, go for it.</del>

Nevermind, it totally does work on mobile. If someone was in the middle of working on this, I'm sorry, but this only makes your efforts more hilarious.

## [<span class="octicon octicon-link"></span>](#acknowledgements)Acknowledgements

I snatched the starting point for this venture from The Onion's most excellent [fartscroll.js](http://theonion.github.io/fartscroll.js/), which I whole-heartedly [encourage](http://zweig.co/jankyscroll/example.html) you use alongside **jankyscroll**.

I'd like to publically shame James Adam Buckland for encouraging this.

# License
Copyright (c) 2015 Benjamin Zweig

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Also, give credit, ya doofs.
