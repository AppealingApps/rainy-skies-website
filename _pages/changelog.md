---
layout: page
title: What's New
include_in_header: true
---

<br>

### <a name="roadmap"></a>[`Roadmap`](#roadmap)
* iOS 26 and Liquid Glass support

### <a name="upcoming"></a>[`Upcoming`](#upcoming)
# <a name="2.1.0"></a>**[Version 2.1.0](#2.1.0)**
##### Highlighted Changes
* You can now select to see every hour in the hourly bar dropdown menu, and there is a new setting in "Hourly" settings to make that the default
* Added "Last 30 Days" weather screen, accessible from a button on "Weather" screen daily weather (Silver only)
* Added "Location Info" screen, accessible from the (i) button on the Locations screen containing a map of the location and monthly statistics

##### New Features
* Added a setting in "Current Weather" settings to not show the mini radar view during precipitation
* Added zoom buttons to the radar screen
* Added a default zoom setting in "Radar" settings
* Added separate settings for radar and satellite opacity in "Radar" settings
* Added a setting (on by default if the "Differentiate without Color" accessibility option is enabled, otherwise off by default) to show a condition icon in the "Weather" screen hourly bar
* Added a "Sync" status to the Settings screen
* Added an "Hourly" setting to change the precipitation percentage where snow or rain is shown in the hourly bar

##### Bug Fixes
* Improved hiding the top and bottom "Weather" screen bars on scroll
* Fixed some colors in the app not using the selected accent color in "App Display" settings
* Fixed the layout of the "Help" screen
* Unified how the Settings screens handle free users
* Maybe fixed the Watch app resetting constantly
* Fixed widgets not showing based on precipitation chance

##### Other
* Updated dependencies
* Improved reliability of fetching weather
* Updated the "About the Author" screen
* Updated some Settings layouts

##### And Finally...
What kind of music should you listen to while fishing? 
...
...
...
...
Something catchy! (☞ﾟ∀ﾟ)☞

### <a name="changelog"></a>[`Latest`](#changelog)
# <a name="2.0.2"></a>**[Version 2.0.2](#2.0.2)**
##### Highlighted Changes
* Enabled Mac Catalyst! I haven't tweaked Rainy Skies much for it yet, but it should work a bit better than it used to.
* A new icon for Easter 2025!

##### New Features
* Added a Customer Center in Settings->Help and if you're a subscriber on the "You're a Member" cell.
* A brand new paywall for non-subscribers.
* Added some extra info to help e-mails to help me debug any issues you may be having.
* If the app hasn't been used for more than 5 minutes, coming back should now bring you back to the weather screen.

##### Bug Fixes
* Fixed the app store link in the share button on the Settings screen.
* Fixed the Radar screen's legend having a funky layout. In this case, less funk is actually a good thing.

##### And Finally...
What do you call a boomerang that won't come back?
...
...
...
A stick. (☞ﾟ∀ﾟ)☞

# <a name="2.0.1"></a>**[Version 2.0.1](#2.0.1)**
##### Highlighted Changes
* Apple Watch circular and corner complications now include color.
* Locations are now one line (no country). There is a new setting to include the country as well.

##### New Features
* Added a share link to Settings.

##### Bug Fixes
* Fixed loading the app on iPad in landscape would show the portrait UI.
* Settings -> App Display -> Accent Color is now sorted alphabetically.

##### Other Changes
* Updated analytics (I believe that privacy is a fundamental user-right, and _all_ of my analytics are 100% anonymous. Your data will never be sold. See the privacy policy for more details.)
* Updated dependencies.
* Replaced the Threads link in Settings -> About with a Bluesky link.

##### And Finally...
Why did the chicken cross the playground? 
...
...
...
To get to the other slide. (☞ﾟ∀ﾟ)☞

# <a name="2.0.0"></a>**[Version 2.0.0](#2.0.0)**
##### Highlighted Changes
* Radar! You can now view precipitation radar and cloud cover on a map. Tap the "Radar" tab at the bottom (or on the side on iPad) to see it. If precipitation is on the way, you'll see a mini-radar view right alongside the next-hour precipitation chart.
  * There are a number of color schemes and options in the new "Radar" settings screen.
  * If you have a free account, you'll only see the current radar. On Silver, you can see past and future radar (up to 30 minutes in the future).
* Apple Watch app! You can see much of the same information—but no radar, yet :( —in the new Apple Watch app. The same refresh rate rules apply on the Apple Watch app as they do in the main app. Many complications and widgets were added as well.

##### Other New Features
* The daily row precipitation icon is now a snowflake if the precipitation that's coming is...snow. That was probably pretty obvious, huh.
* When you select a new location, the app will now dismiss the locations screen.
* Added a little sunrise or sunset image next to the sunrise / sunset time.
* When you send a bug report e-mail, logs from the app will now be added to help with debugging any issues you may have.
* The locations group in the iPad sidebar is now expandable and collapsible.
* You'll notice some new animations in the app.
* You can now change the default accent color of the app in Settings -> App Display.
* Hourly bar colors are now customizable in Settings -> Hourly Weather -> Condition Colors.
* Tapping and holding on hourly weather provides a shortcut to Hourly Weather settings and a glossary popup.
* Daily Settings now let you use daytime-only temperature (you can also change this on the main weather screen next to Daily Weather).
* You can now hide the navigation and tab bar when you scroll down by turning on the option in Settings -> App Display.
* Added a new "Silver" icon for Silver subscribers.
* Widgets are now properly accentable on iOS 18+.
* Settings is now in the tab bar / sidebar.
* Various other little text and styling adjustments.

##### Bug Fixes
* The "Review the App" button in Settings now takes you to the App Store review screen because the pop-up wouldn't work in some cases.
* Fixed deleting the current location.
* Fixed the daily weather for the current day. When expanded, it will no longer include hours from tomorrow.
* If pulling weather fails in widgets, it will now use cached data.
* Fixed geocoding not working in some cases because we did it too frequently.
* Updated wording of "Pro Icons" to "Silver Subscription Icons" on the app icon screen.
* Fixed share screen crashing.

##### And Finally...
Why are libraries so tall? 
...
...
...
Because they have many stories. (☞ﾟ∀ﾟ)☞

# <a name="1.2.3"></a>**[Version 1.2.3](#1.2.3)**
##### Highlighted Changes
* Updated with support for the iPhone 16 line and dark icons on iOS 18.

# <a name="1.2.2"></a>**[Version 1.2.2](#1.2.2)**
##### Bug Fixes
* Reduces duplicate weather alert notifications even further.

# <a name="1.2.1"></a>**[Version 1.2.1](#1.2.1)**
##### Bug Fixes
* Fixed the notification tip continually reappearing, even after you've dismissed it (fingers crossed)
* Fixed weather alerts disappearing and reappearing, and duplicate notifications being sent. Really sorry about that one!

# <a name="1.2.0"></a>**[Version 1.2.0](#1.2.0)**
##### Highlighted Changes
* A revamped hourly data type picker. That's a really long name for the menu that lets you pick what kind of hourly data you're looking at, like "temperature" or "precipitation chance". That whole menu has been given a makeover to make it quicker to use and totally customizable. (Silver subscription required)
* You might notice a little toggle next to the minutely precipitation chart the next time it's raining. You can now see the percent chance of rain over the next hour too! (Silver subscription required)
* Current weather has been given a bit of a glow-up. You can now swipe on the mini data blocks to see more. Press and hold to get to the settings menu and customize away. (Silver subscription required)
* Notifications! Maybe that idea doesn't excite you yet, but give it a whirl. It has probably been one of the most difficult features to get right, but also one that's been far more useful than I would have thought! You can get summary notifications for today's and tomorrow's weather, and alerts when severe weather is entering your area. (Silver subscription required)

##### Other New Features
* If you return to the app after a while, we'll deposit you at the top of the weather screen.
* After you've been using the app for a bit, we'll ask how you're feeling about the app. You have no idea how much a good review means.

##### Bug Fixes
* Adjusted how weather alerts look on the weather screen so they'll show their full title more often.
* It felt odd that the snow icon was a snowflake, but the icon for rain was clouds and rain. Now the icon for snow is clouds and snow to match.
* When you would open weather alert information, there was a weird visual glitch at the bottom of the web view. That's been polished off.
* The bar on the side would show "cloudy" (gray color), even when it was mostly sunny outside. Fixed!
* Adjusted the hourly detail screen to fix the text being all caddywompus.
* Adjusted the precipitation intensity chart to not hit the ceiling so often.

##### What's Next
It's summertime where I am. That means vacations and iOS announcement season. The next update of Rainy Skies will aim for the fall when the next version of iOS releases. I hope you all have a safe and blessed summer (or whatever season you are in)!

And, finally...

What’s a ghost’s favorite summer treat?

...

I-scream!

# <a name="1.1.1"></a>**[Version 1.1.1](#1.1.1)**
Not much new here, just a little housecleaning!

##### Bug Fixes
* Fixed a bug with the next-hour precipitation chart. It would always show extremely light rain, even during a storm. Our attempts to change the weather failed, so we'll return to showing you what's happening out your window.
* Fixed a bug with the tip jar where the image would load and then load again. 

What's Forrest Gump's password? 
...
1forrest1

Thanks for using Rainy Skies! We'll have new features for you...when they're ready. Grace and peace!

<br>

### `Previously`
# <a name="1.1.0"></a>**[Version 1.1.0](#1.1.0)**
##### Highlighted Changes
* New Free App Icon “Bold White” — We’ve introduced a fresh app icon that’s bolder than a banana trying to impress its peel. It’s so white that it makes snowflakes jealous. Plus, it’s free! 
* Locations Sync Between Devices — Your weather preferences are now more synchronized than a perfectly choreographed rain dance.
* iPad Split View: Weather and Locations — It’s like having a meteorologist and a GPS navigator co-hosting a reality show. Tune in for the drama!
* “What’s New” Screen — We’ve added a “What’s New” screen because everyone deserves a little suspense in their weather app experience. It’s like opening a fortune cookie, but instead of lucky numbers, you get juicy app updates. Spoiler alert: It’s all about the weather (and maybe a sprinkle of magic).
* Custom Widget Locations — Widgets now let you set custom locations. Want to know the weather at the North Pole? Done. Curious about conditions on Mars? Well...we can't do that...yet.

##### Other Changes
* Paywall Upgrade: Now with Pizzazz! — Our paywall has undergone a transformation. It’s no longer a dull toll booth; it’s a glittering gateway to premium features.
* Settings Screen Shuffle — We reorganized the settings screen like a game of musical chairs. It’s sleeker, snazzier, and more intuitive.
* Subscription Sleuth Mode — We’re now Sherlock Holmes for subscriptions. If we suspect you’ve subscribed, we’ll discreetly investigate. Expect a polite inquiry: “Excuse me, dear user, do you have a subscription? Mind if we restore it on your new device?” Elementary, my dear Watson.
* Dot-Dot-Who's-There? — New app icons now wear a tiny dot until you give them attention. It’s like they’re saying, “Hey, I’m here! Look at me!” Treat them kindly; they’re sensitive. And remember, every time you ignore an icon, a pixel sheds a tear.

##### Bug Fixes
* Chart Bugs Squashed — Our charts were acting glitchier than a robot doing the cha-cha. But fear not! We’ve debugged them faster than a caffeine-fueled programmer during a hackathon. Now your weather graphs are smoother than a jazz sax solo.
* Weather Alerts: No More Hide-and-Seek — Weather alerts were playing peekaboo, hiding from the screen like mischievous sprites. We’ve scolded them and put them back where they belong. Now you’ll know about storms, rainbows, and unicorn sightings in real-time.
* Farewell, “Location 1” Mystery
* Various other bits and bobs

Why did the scarecrow win an award? Because he was outstanding in his field!

Remember, our app is like a weather wizard’s spellbook—full of surprises, enchantments, and occasional hiccups. Enjoy the updates, and may your forecasts be as accurate as a cat predicting rain (which is to say, not very). Happy weather-watching!

# <a name="1.0.4"></a>**[Version 1.0.4](#1.0.4)**
Happy Holidays! The only new item in this update is a Christmas 2023 app icon for subscribed users. I have some great new updates in the works that I think you'll really love. Best of wishes to you and your families during this holiday season, and I'm praying for a wonderful new year for all of you.

And, of course, here's your joke of the update!

How much did Santa pay for his sleigh?
...
...
...
Nothing. It was on the house.

# <a name="1.0.3"></a>**[Version 1.0.3](#1.0.3)**
Ahoy, app aficionados! This update is jam-packed with fixes and tweaks. Let's dive into the changes:

Fixes:
- We've mastered the art of instant weather metamorphosis. Toggle those temperature units, and watch the numbers change faster than our Michigan weather.
- Fixed selecting hours on the hourly detail screen now changes the info data properly – It was a bit like trying to teach a cat to fetch. But fear not, the hourly details now obey your taps like a well-trained butler.
- Fixed free version location limit alert now shows up at the right time and ISN'T IN ALL CAPS – We realized the alert was shouting at you like an overexcited sports commentator. It's now speaking in a more civilized lowercase tone.
- Fix weather pull date – Our weather pull date footer has been a bit of a time traveler itself, jumping back and forth. Apologies for any confusion; we've grounded it and sorted out its timeline issues.
- Fix the "Member Since" date text for subscribers – It turns out, our app was a little confused about its age. It's not Benjamin Button; we've corrected the "Member Since" date to reflect your subscription's true age.

So there you have it, brave users! This update is like a magician's hat—full of fixes, surprises, and maybe even a rabbit or two. Keep enjoying the app, and remember, if you find any more quirks, consider them part of the charm. Stay quirky!

And of course, your dad joke for this update:

My wife said I should do lunges to stay in shape...
...
...
...
That would be a big step forward!

# <a name="1.0.2"></a>**[Version 1.0.2](#1.0.2)**
Hey there, fearless app explorers! We're back with our first little app update, and this one's all about your senses. Get ready to feel the app like never before.

##### Features:
- Your hands just got a new best friend. Feel the loading, errors, and taps with a touch of style. It's like a virtual handshake every time you use the app.
- We've set your widgets free! They're like little weather detectives now, gathering their own info. No more relying on the weather app to spill the beans.

##### Fixes:
We squashed some bugs, and the results are both beautiful and a little quirky.
- The current weather widget was acting up, but they're back in business now. No more sudden weather widget meltdowns.
- We're using location coordinates so fuzzy, they're almost cuddly. Be aware that this update will invalidate all your existing caches.

We've fixed up the UI a little bit, to make things just a little bit fresher.
- Fixed the dew point chart not scrolling – It was more stuck than a lollipop in summer. Now, it flows like a river.
- Fixed bottom padding of weather ad when it wasn't on screen – Padding is great, but let's not get carried away. We've fixed it so it stays where it's supposed to.
- Don't show refreshing UI when no refresh is needed – No more fake refreshes.
- We used to be a bit forgetful when we last checked the weather at the bottom of the weather screen. Now we're spot on, like a well-trained golden retriever.

##### Performance Improvements — It's like trading your bike for a rocket.

So there you have it, folks. This update is all about feeling the vibes, making things look right, and performing like a champ. Enjoy the sensory journey, and as always, keep those feature requests and bug reports coming. We love hearing from you, even if it's to say, "Hey, your app is the best thing since sliced bread." Stay sensational!

Oh yeah, and here's your dad joke for this update:

Why don't skeletons fight each other?

...
...
...

Because they don't have the guts!

# <a name="1.0.0"></a>**[Version 1.0.0](#1.0.0)**
The initial release of the app! Has the weather screen, supports Apple Weather, looks pretty good 😏
