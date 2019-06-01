# OpenHAK Hardware
## OpenSource Health Activity Kit Hardware Files

KiCad files for the beta OpenHAK boards.


### WARNING: Siblees don't exist!

Hi, here you'll find everything that you need to make yourself your very own OpenHAK! If, that is, you have any spare [Simblees](https://www.digikey.com/product-detail/en/rf-digital-corporation/RFD77101/1562-1034-ND/5723430) lying around. Should you do have some Simblees that are just taking up space, then you're in luck! Simblees are very well trained to handle reflow with a hot air gun or toaster oven many, many times. Trust me, they are tough buggers. If you *don't* have any Simblees propping open your window or shimming up your wobbly cafe table, then you're out of luck... Or are you....?

## What's going on?

**O**pen**H****A****K** is an **O**pen source **H**ealth **A**ctivity **K**it. Right out of the box you can wear it on your wrist (or your ankle, if you're in to that kind of thing) and start tracking your steps and heart rate with a mobile app. No kidding. All of it is open-source and ready to use, modify, and share. We *were* going to call it an **O**pen **S**ource **H**ealth **I**nformation **T**racker, but we don't want to confuse people. 

## Who owns the data?

Data? What data? We don't own anything. We don't keep secrets from you, or try to distract you with shiny things while we stuff your data into our AI mattress monster. No. All the data is yours. YOU can delete it or share it or analyze it or whatever it. We don't care, just don't ask us for it 'cause we don't have it. It's yours and it gets stored on your phone, or tablet, or whatever you hack the OpenHAK to spit your data into.

## What's in the box

So glad you asked. Right now, we are engaging with our beta testers and the hardware has some features that we are excitedly happy to tell you about.

* BLE
	* Yes, it's a Simblee, but it's still a pretty awesome BTLE module that can do some incredibly cool stuff. We are supporting the original Simblee board files for Arduino and our very own OpenHAK board variant that offers cool features. The module comes with Nordic's DFU library installed, and we've made it easy with our [hardware variant](link here) for you to write your own firmware and upload it over the air from you're phone to your OpenHAK
* BMI160
	* This multi-axis MEMS monster is what we're using to count your steps, and interface with your finger tapy tap taps. We are revealing full access to it's inner guts so you can transmogrify the OpenHAK into a gesture controller so you can control your monster robot to slay your adversaries monster robot with a simple gesture.
* MAX30101 
	* Yes, it's a MAX integrated heart rate sensor that plays well with [link to sparkfun library]. In the BETA version we are using the MAX3010**1** variant. If you've ever used them they are super fun to play with. **We know.** It's not easy to get heart rate off of the wrist. It's not impossible, but it's hard. That's part of the reason why we're doing this, to see how an open-source community can come together and find creative ways to solve this among many problem.
* ACCESSORIES
	* We are breaking out a handful of pins (8 for the BETA version) that are user accessible. These are useful as a wired program interface. And, um, maybe driving an OLED display? To, maybe, let you know when your friend is texting you ('cause it's connected to your phone). It could also drive an ERM (vibrator, ahem) to provide haptic feedback. The point is that since it's open-source, it's up to you. We will put up PCB design guides and templates so that you can create the thing you want to wear on your wrist/ankle/ahem. 

## What else

The board is fit with physical features that will capture pins from an 18mm watch band. 18mm is a standard watch band size so you can accessorize with bands to your heart's delight!

## And
We placed the MAX3010x sensor all by itself on the (recommended) skin side of the board. We did this to facilitate enclosure design. We have a prototype case (link) that performs well under reasonable circumstances (no, we haven't mountain-biked in a wintery mix with it yet...).


If you've gotten this far then you're only halfway down! Keep mining this repo and, don't be shy, we're only an issue away! 
