---
layout: essay
type: essay
title: "Bootstrap, A Great Tool to Have in the Bag"
# All dates must be YYYY-MM-DD format!
date: 2024-02-22
published: true
labels:
  - Software Engineering
  - Web Development
  - UI Frameworks
  - CSS/HTML
---

<div style="float: left; margin-right: 10px;">
  <img width="300px" src="../img/shocked-pikachu-css.jpg">
</div>

This week was my first week using BootStrap 5, or any UI framework for that matter. Before this, I had spent a couple of weeks learning HTML and CSS. I built very basic web pages, nothing fancy whatsoever, and I actually liked what was showing up in the browser. It was simple, no frills, no fluff, and it worked. But after seeing what can be done with Bootstrap, it’s hard to argue against the efficiency of a UI framework.

## Ohh, Shiny!

This simple web page built with normal HTML/CSS didn’t take long to make, but there was a decent amount of styling put into it. With virtually no CSS except to change the colors of a couple text items, our retrospectively clunky columns and navigation menu we put together were now built with just a few magic Bootstrap words. Our new navigation bar even sports a sleek dark background and stays visible at the top as you scroll! That probably would have been more useful had our columns not fit snugly into the width of our browser window.

## Vote 'No' For Horizontal Scrolling 

That brings us to probably the biggest appeal of Bootstrap, responsive web design. Had we been rolling with plain CSS, and maybe told the history of a few more browsers (which would also muddy up our styling), we’d have to make contingencies for varying screen widths, unless we wanted our web page to scroll horizontally. Nobody likes horizontal scrolling, though. So do we make the text smaller, or do we reduce the padding? Do we have additional histories wrap back around, conjure up an intentional horizontal scrolling mechanism, or abandon the column idea altogether? 

<div style="float: left; margin-right: 10px;">
  <img width="300px" src="../img/bad-scaling.jpg">
</div>

The beautiful thing about a responsive UI framework is that it’s already thought about those questions. With a magic word, just a class selector, we access its underlying styling. A selectors styling can be either quite simple like changing the color and background color, or rather extensive like directing the component how to respond to changing window sizes by adjusting font size, padding, wrap, form, etc.

## Look At My Cool New Gadgets!

It’s not just the responsiveness though that a UI framework brings. Usually provided is a plethora of included components ready-made for integration into a website. Components such as a navigation bar that transforms into a three-lined hamburger menu when compressed or a section on your page whose content changes depending on the chosen tab are reduced to just a couple of class selectors. I recreated a local organization’s website so I could get accustomed to Bootstrap and decided to use a few of its components just for fun. 

I was impressed with how simple it was to implement them. It still takes some tinkering with the selector choices and locations, but there is no additional styling or scripting required to get it functioning. All of this efficiency and simplicity doesn’t mean it’s easy, though, as there is a boatload of selectors and interactions to get familiar with.

## Don't Try To Screw A Nail With A Hammer...

Bootstrap cannot completely replace CSS. It would be insane, if not impossible, for any framework to include literally every little possible customization option. Custom styling will most likely still need to be done, even if only for simple things like color, font, or spacing. And there will undoubtedly be times where Bootstrap, or whatever framework, cannot create the component or effect desired for the website. At the end of the day, it’s just a tool to make life easier. A developer can be great with tools but still not be a skilled craftsman.


