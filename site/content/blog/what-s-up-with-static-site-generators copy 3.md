+++
date = "2019-07-29T23:00:00+00:00"
description = "Static site generators provide a clean, lean website without a database. Let's discuss how that can benefit you!"
featured_image = "/uploads/hugo-design.jpg"
ogdescription = "Static site generators provide a clean, lean website without a database. Let's discuss how that can benefit you!"
ogimage = "/uploads/hugo-design.jpg"
ogtitle = "What's up with static site generators?"
summary = "Static site generators provide a clean, lean website without a database. Let's discuss how that can benefit you!"
title = "What's up with static site generators?"
twitterdescription = "Static site generators provide a clean, lean website without a database. Let's discuss how that can benefit you!"
twitterimage = "/uploads/hugo-design.jpg"
twittertitle = "What's up with static site generators?"

+++
So we are in the process of moving our portfolio website to Hugo. Having seen what Smashing Magazine achieved, we wanted a piece of that. Plus it gives us the chance to brush up on our development skills.

Whilst we love Wordpress, we do find myself being propped up by the likes of Elementor and Beaver Builder.  They have their use cases, especially for clients on a budget that need websites built quickly. There is of course a comprise between design and code. The output of a pagebuilder a garbage, no matter which one you use and over time you will find that the site will slow down.

Then of course you need plugins to combat the speed.

With a static site generator, you don't have to worry about any of that. You get out what you put in. No extra divs, spaces, code that does not need to load. **It's beautiful!**

So our current setup is as follows:

Hugo + Github + Netlify

We are using the following for development:

* **Visual Studio Code** for markup
* **Gitkraken** for managing our git repository (we prefer it over typing out the same commands over and over again!)
* **Prepros** for minify and concat

We could have used gulp for minify and concat, or even hugo pipes but we are still learning!

We are using forestry.io to manage content, and have even working out how to create our own page builder using something called <a href="https://forestry.io/docs/settings/fields/blocks/" target="_blank">Forestry Blocks</a>