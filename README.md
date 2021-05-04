![](https://javascript30.com/images/JS3-social-share.png)

# #JavaScript30 Challenge Review: A JavaScript Honeymoon

Captain's Log, Stardate 98931.76. I have recently decided to undertake the [#JavaScript30](https://JavaScript30.com) coding challenge. During the next 30 days I will be committing myself to spend a little more time working with JavaScript by building some really cool shit.

Take the challenge at [JavaScript30.com](https://JavaScript30.com), be sure to checkout more of [Wes Bos' courses](https://wesbos.com/courses) and show your support!

----
## Day 1: JavaScript Drum Kit
-----
*Saturday May 1st, 2021* 

![](challenges/01_-_JavaScript_Drum_Kit/screenshot.png)

[**Source Files**](https://github.com/huntertrammell/JavaScript30/tree/main/challenges/01_-_JavaScript_Drum_Kit)

[**Live Demo**](https://huntertrammell.github.io/JavaScript30/challenges/01_-_JavaScript_Drum_Kit/)

**TIL/Thoughts**: This was great, I think the biggest takeaway for me was the ```transitionend``` event listener. This was an event type I have not had the pleasure of working with yet. By listening to when the CSS transition had completed on the element we were able to remove the style that set the glow around the key.

Another thing I found helpful was taking a look at the [different properties and methods](https://www.w3schools.com/jsref/dom_obj_audio.asp) related to the ```audio``` tag. We used the ```currentTime``` property to rewind the audio so that when ```audio.play()``` is called on the same element there is no delay.

I opted to try to build the app myself before watching the tutorial and without reviewing the solution. My approach wasn't quite as eloquent as Wes' -- and that is ok. This challenge is meant to help reinforce and invigorate your JavaScript knowledge. I happily refactored and gained some good insight on how to write cleaner code.


----
## Day 2: JS and CSS Clock
-----
*Sunday May 2nd, 2021* 

![](https://huntertrammell.github.io/JavaScript30/challenges/02_-_JS_and_CSS_Clock/screenshot.png)

[**Source Files**](https://github.com/huntertrammell/JavaScript30/tree/main/challenges/02_-_JS_and_CSS_Clock)

[**Live Demo**](https://huntertrammell.github.io/JavaScript30/challenges/02_-_JS_and_CSS_Clock/)

**TIL/Thoughts**: I haven't worked with ```setInterval``` much since first learning how to code building stopwatches etc, but i'm really thankful for this exercise for giving me a reason to fiddle! Using this method to power animations is really cool and I can see it being useful in creating more complex animations, i've been wanting to experiment more with animations and am excited to utilize this more in future projects.

I did a bit of refactoring as a challenge to myself. The build on this was fairly quick as it utilized a lot of the same code - that being said, I went ahead and moved the degree calculating variable and the style.transform into their own functions and used arguments to pass in the data that was unique to the different time measurements. 


----
## Day 3: CSS Variables
-----
*Monday May 3rd, 2021* 

![](https://huntertrammell.github.io/JavaScript30/challenges/02_-_JS_and_CSS_Clock/screenshot.png)

[**Source Files**](https://github.com/huntertrammell/JavaScript30/tree/main/challenges/02_-_JS_and_CSS_Clock)

[**Live Demo**](https://huntertrammell.github.io/JavaScript30/challenges/02_-_JS_and_CSS_Clock/)

**TIL/Thoughts**: I haven't worked with ```setInterval``` much since first learning how to code building stopwatches etc, but i'm really thankful for this exercise for giving me a reason to fiddle! Using this method to power animations is really cool and I can see it being useful in creating more complex animations, i've been wanting to experiment more with animations and am excited to utilize this more in future projects.

I did a bit of refactoring as a challenge to myself. The build on this was fairly quick as it utilized a lot of the same code - that being said, I went ahead and moved the degree calculating variable and the style.transform into their own functions and used arguments to pass in the data that was unique to the different time measurements. 

----
## Notes
----
Thanks to [@palashmon](https://github.com/palashmon) for the tracker inspiration 🙏🏻
