We recently had a couple of issues where we needed to know what our websites look like in different locations. We wanted to know how one of our sites ranked locally in New York City, and we needed to make sure another site was working in India. We're a growing business, but we don't yet have satellite offices in those locations. But with the help of Google Chrome Inspector, we were able to make it appear that we were browsing from Mumbai and New York City.

So how did we do it?

First, fire up your Chrome browser. (Other browsers may have similar capabilities, but these instructions are for Chrome.) Then open **Chrome Inspector**. I typically do this by simply right clicking on a web page, anywhere, and selecting `Inspect`. The inspector will open up on the page. (Lagniappe hint: if the Inspector is stuck in your window taking up most of the room, you can go into the Inspector Settings and change "Dock Side" to pop the Inspector out into its own window. I recommend you do this.)

I hope many of you are already familiar with Chrome Inspector, but I'll try not to skip any steps in case this is all new. (And if you find it confusing, please [email me](mailto:david@onlineoptimism.com) email me and I'll try to explain and improve these instructions.)

Now that you have Chrome Inspector open, press `Control+Shift+P`, `Command+Shift+P` if you're on a mac. This Opens the **Command Menu**. The Command Menu, not surprisingly, contains a lot of commands you can give the Inspector, so it'll do things. In the space at the top of the Command menu, type "Sensors." That filters down to the command you want: Show Sensors. Click that and the Sensors tab will appear in the drawer (i.e., the space at the bottom of your Inspector window).

Now for the fun part!

In the Sensors tab, the first thing you'll see is the Sensor for **Geolocation**. That sensor is how Google Chrome knows your location, so you can see the local restaurants and bars and such when you allow Google to know your location. This sensor strongly affects the search results you see in Google searches. So, if your remember the beginning of this blog post, what we wanted to see is how our New York City client came up in searches that originate in New York City. Since we aren't there, here's how we pretend to be.


