---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


># TL;DR
> Dell is a totally mismanaged company. Their computers have extremely high failure rates, their design is haphazard, 
their support is abysmal.



# What GPT-3 thinks about Dell?
I asked GPT-3 what it thinks about Dell laptops. Here is what an AI learned from summarizing the internet

>Dell laptops are horrible for a number of reasons. First, they are extremely overpriced. You can easily find a better laptop for the same price from another manufacturer. Second, the build quality is very poor. The plastic is flimsy and the hinges are known to break easily. Third, the customer service is terrible. It is very difficult to get in touch with a human being when you have a problem, and even when you do, they are often unhelpful and unprofessional. Finally, the laptops themselves are often unreliable. They are known to overheat, have screen flickering issues, and randomly shut down.
>All of these factors combine to make Dell laptops a terrible choice for anyone looking for a new laptop. 
> Save yourself the headache and go with a different brand.
  

# Symptoms of disease
When a person or company is sick, often external, visible symptoms will appear. You don't need to buy their 
hardware and have it fail on you to realize the company is totally broken.

## Two online stores
Dell has two online stores with different prices and different stocks. There is the [primary store](https://www.dell.com/en-us/shop/) and there is the [premier store](https://www.dell.com/en-us/lp/dell-premier-deals). 
Customers need to search both stores to find the product they want. When I bought my laptop it was not in stock in the normal store but was in stock and a different price
in the premier store.

## What is with the naming?
There is a laptop named "New XPS 15". Who the fuck names a laptop "New XPS 15"? How am I supposed to talk about it in a year when Dell creates another XPS 15? By the way, there used to be a laptop named "New New XPS 13"! I wish I had a screenshot of that one. 
This is a screenshot of their XPS lineup at time of writing this:
![image](/assets/xps-lineup.png)
They can't even get the CSS right on their website. 

## Too many models
They produce far too many models of laptops and 2-in-1. There are currently 285 models, it takes 24 pages of store just to display them all! (Compare this to Apple which is a far larger company and has ~5 laptop models)

It is impossible for them to properly design, test and support such a large number of different models.
This is one of the reasons that their machines and support are such low quality. They don't try to get it right, their business model is to produce
a large quantity of models and obtain sales through bruteforce rather than quality. 

Here are two screenshots:
![image](/assets/number-of-models.png)
![image](/assets/pages-of-laptops.png)

**Look at all these Inspirons! Inspiring isn't it?! Great webdesign btw!**

![image](/assets/lineup.png)


# Unreliable hardware
The internet is full of people complaining about Dell's hardware. There are tons of people on Reddit with countless horror stories
of repeated hardware failure and poor support (despite a promise of "premium" support).

Here is an example:
>We've been a Dell shop forever, and we used to sing the praises of their hardware and support. The older laptops were built like absolute tanks, and ProSupport was a dream to work with.
>Starting a couple years ago, the laptops we'd get from Dell had a ~40% chance of having a swollen / exploded battery within 2 years. ProSupport used to be NBD, now it's sometimes taking 3-4 business days for onsite repair.
> 
>We just got a shipment of laptops and out of the first 3 we deployed, 1 had a bad USB port, 1 had a nonfunctional trackpad, and 1 had a broken display. It's like they've just completely stopped doing any sort of quality control.
>
> From: https://www.reddit.com/r/sysadmin/comments/qgybkv/rant_is_it_me_or_has_dells_quality_control_gone/
 
If you look at the comments you will see that many people agree with this poster. Of course, it's hard to know the true failure rate
of Dell laptops but 40% in 2-years seems about right looking at anecdotal evidence on the internet. My laptop failed after 1 year of very light use and no abuse.
Of the many Macbooks I have owned over the last 10+ years, not a single one has failed.


# Poor design.
The design of their machines is so bad I have come to the conclusion that no one is designing them. I know this sounds like a ridiculous claim,
but I am quite certain it's true. I happened to work on a laptop project with a Dell competitor and saw how their "design" process worked. They wanted
to make a laptop with an outstanding webcam, that was **the** purpose of the laptop. A project manager decided what type of camera and lens the laptop should have,
without thinking about the consequences such as how large the bezel will be, the field-of-view of the chosen lens, how the resolution will interact with video conferencing software, etc...
There was no testing done beforehand to make sure the camera/lens/ISP achieved the performance they were looking for. They made a decision, started going into production and then discovered  
that the camera was a horrible choice. They did not build a few test devices and do user testing to make sure they were making a good decision. Unbelievable!

I think a similar thing is happening at Dell. There are so many obvious design mistakes(google them) it's amazing these machines go into production. For example:
it was impossible to open the screen on the XPS without using two hands. One hand was needed to hold down the base and the other to pry open the screen. Clearly nobody tested this before it went into production.

Another example is using a 4k screen on a 13" laptop. Much better in terms of battery life and price to use a 2.5k screen (Apple does this). Humans can't tell the difference. Why did they use a 4k? Probably because some non-technical project manager thought it was a good idea
and did not think about the consequences. 

**Look at this camera positioning. Great for showing off your nose hairs!**
![image](/assets/camera-position.png)


# Bloatware
Dell laptops come with a ton of pre-installed Bloatware. 
![image](/assets/crapware.png)

[This dude claims its using 30% of GPU](https://www.youtube.com/watch?v=5N7aYtkzKJc)


# Support
My laptop broke, hard drive failure. I knew Dell laptops were unreliable when I made the purchase(thanks reddit) so I purchased two-year premium support/warranty with the machine.  

**TL;DR it took 37 days for Dell to fix my laptop.** They incompetence of their support team is so absurd its entertaining. [You can see shit show for yourself by looking at the screenshots of my conversation with them
](https://github.com/Jakobovski/dontbuydell/tree/master/support-screenshots). Take note of the dates and times.

First thing I do is open a support ticket online with my service tag. They tell me I need a new hard drive and I have to fill out a form with my address. Problem #1. The form does not allow me to select any country other than the USA.
There is a dropdown for countries but for some reason its disabled (symptom of corporate disease). OK so I need to talk to a live person. Great, they have Whatsapp support! I start the chat and get a bot that sends me the same message twice.
Why twice? I have no idea. Whatever not a big deal. 

![image](/assets/whatsapp-support.png)

I finally get through to a human and get them to order the replacement part! 4 days later this is the situation: 

![image](/assets/service-history.png)

Just look at that and tell me WTF is going on. So they scheduled an appointment (without telling me) and then they cancel it without telling me and then reschedule. No alerts, no SMS, no email, nothing. 
Are the parts in stock or not? Is the technician coming in a 4-8 hour window ending at 10:40 am? So they may come at 3am?  I still have a broken laptop and don't know when it's going to be fixed.

Turns out they entered the wrong address on the service order. They entered the address of my account, and not the address I gave them. I am currently out of the country, which means they shipped the part to the wrong country. Now I need to wait again for 4
day for the part to arrive. I tell the agent this, they tell me they will update the service order. 24 hours later the service order is still not updated.

Dell kept on telling me there was some technical issue and they could not update the address on the service order. They told me they would update me. Days and weeks went by, each representative had a different story, the issue did not get fixed.
One support agent told me to re-register the laptop, another told me to drop it off at some repair site, another one told me that there was nothing pending and I needed to start the process again.

Eventually someone was able to dispatch a technician. The technician was given the wrong address again and went to the wrong city. At least this time it was in Israel, I talked to him on the phone, gave him my correct address and he ended up coming the next day.

All in all *it took 37 days, for Dell to fix my laptop*. Let me remind you that I had paid for the premium worldwide pro support.


**Here is another nice support story**
>In June I got a new XPS13 (without the touchbar), preloaded with linux. Upon arrival, the camera and fingerprint reader did not work. The battery lasted about 2 hours and the screen literally fell out. After 2 days of frustrating tech support calls, they finally agreed to ship me a replacement.
> 1 month later, no replacement arrived. Many calls to support yielded no answers. I finally got them to refund my order and cancel the replacement.
>
> A very bad experience for me and I will never buy a Dell again.
> (from louffoster on HackerNews)

# Poor linux support on Developer Edition
Dell sells a laptop that is made for linux! Sounds great right? Not exactly. There are serious driver issues, the laptop does not sleep when closing the lid and thus the battery dies very fast, Dell refuses to fix this problem [here](https://www.dell.com/community/XPS/XPS-13-9310-Ubuntu-deep-sleep-missing/m-p/8056343#M91204). It's impossible 
to download the OEM linux image if you don't have the service tag. There are lots more issues which you are welcome to Google. 


# Discussion of DontBuyDell.com on HackerNews
See what other people think of Dell: [https://news.ycombinator.com/item?id=33342342](https://news.ycombinator.com/item?id=33342342)


# Contribute to this rant.
Are you also frustrated with Dell? Feel free to contribute to this rant. Just create a merge request on Github: [https://github.com/Jakobovski/dontbuydell](https://github.com/Jakobovski/dontbuydell)

