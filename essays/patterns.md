---
layout: essay
type: essay
title: "Implement Patterns, Don't Redesign Wheels"
# All dates must be YYYY-MM-DD format!
date: 2024-04-25
published: true
labels:
  - Software Engineering
  - Design Patterns
---

<div style="float: left; margin-right: 10px;">
  <img width="200px" src="https://i.dailymail.co.uk/i/pix/2017/09/11/22/442AF8F800000578-0-image-a-5_1505167027194.jpg">
</div>

## An Early Bird, I Am Not Meant To Be

Design patterns in software engineering are much like habits developed for morning routines. If I didn’t have any habits, my mornings would be an absolute mess. I’d probably set my alarm for the exact time I want to get out of bed, say 5 AM and be out of the house in 45 minutes. Of course my body needs time to boot up a little bit, so I hit the snooze a couple of times before finally throwing my feet off the bed to propel my body upwards. Now it’s 15 minutes later and I really need to start going, except my brain is still asleep on the pillow. 

So I’m on my own, I can’t think this early in the morning, but my body is telling me I gotta go to the bathroom. I do that, and then start the shower and stand there trying to sleep while the water warms up. Afterwards, I brush my teeth, since I’m still in the bathroom, and I guess that makes sense. I go out and see the time is now 5:30 AM. At this point, I don’t have time to make coffee or breakfast, so I find my clothes, pack my bag, and head out. Oh, I forgot my laptop charger. And it’s raining. I wish someone had told me that.

## No Think, Only Do

Since my brain is of no use for the first hour of my morning, I need to develop necessary habits that will make my routine robotic, but efficient. Most of my evening routine is spent just preparing for the next day: check weather, pack bag, lay out clothes, prepare breakfast/coffee station. With everything done or in view, there’s not much thinking needed, just muscle memory. I set a couple of alarms for five and ten minutes before I want to be out of bed because I know it takes a bit for my body to prepare itself. I fling my legs off the bed and prepare myself upwards, turn the news onto my phone, get water boiling, and go take a shower. 

<div style="float: right; margin-left: 10px;">
  <img width="300px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdxAPBYz9CjeuBFCeEC3mFIC9vjuc7nUWXEicF7fSGkQ&s">
</div>

While I’m showering, I’m tuned into the news to listen for relevant weather or traffic updates. Once I’m done showering, I get coffee brewing, and then make and eat a PBJ sandwich during that time. I pour my coffee, brush my teeth, do my hair, and get dressed. By then, it’s usually about 5:25 AM and I have some 20 minutes to spare: plenty of time to enjoy my coffee. Or, if the news informs me that I should leave earlier, I can forgo the PBJ, do my teeth/hair/clothes while coffee brewing, and take my coffee to go. Either way, my bag is waiting for me at the door.

## Don't Reinvent The Wheel

Just like habits that turn my mornings and evenings into efficient routines, I employ several software design patterns in my projects. There’s the Model-View-Controller framework that separates code into their own purpose-made files. In Manoa Fit Connect, the pages that users see don’t inform them of the logic going on behind the scenes, or how information is stored. They view the information, input the changes or additions they wish to be made, and the logic controller pushes that to the collection model which then updates the page that the user is seeing.

The Publish-Subscribe design pattern is also used. The collections are made into publications that are pushed to the pages that have subscribed to them. I have an event handler, a feature of the Observer pattern, that changes the input fields presented when a specific option is selected. Specifically, when creating or editing a profile, if the user selects the “Other” drop down option for goals or styles, a textbox field appears that allows them to input their own value. None of the patterns are innovative on my part, but they are proven by the software development community and are immensely helpful to the efficiency and familiarity of code.
