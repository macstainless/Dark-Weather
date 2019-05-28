# Dark Weather
A common issue is needing my lights on during the day if there's rain or snow. It's usually dark during these times and it's nice to have lights. That's where Dark Weather comes in.

I released this app a few years ago but the platform security and requirements have changed a lot since then. Also, the old version relied on a weather sensor and most don't have that. As such, I've rewritten this app from the ground up.

Dark Weather monitors a switch for weather conditions. The best way to implement this app is via IFTTT weather monitoring to trigger a virtual switch. When the switch turns on, the mode changes to a "rain mode" that you set up. When the switch is off (rain stopped) then it flips to whatever mode you choose. When that happens, you can choose to have lights turn off. In addition, the app will not leave "rain mode" after sunset. This is a fail-safe so if rain ends during the evening, you're not taken out of your normal evening / night mode.

## The recommended setup is as follows:

1. Create a virtual switch within the SmartThings app.
2. Create two recipies on IFTTT: one to turn the switch on when there's rain and the second to turn it off when the skies are clear.
3. Set up the app to monitor the switch.

## To install this app:

1. Visit the app on GitHub and copy the raw code.
1. Log into the IDE.
1. Click My SmartApps, New SmartApp.
1. Select the "From Code" tab.
1. Paste the code into the box.
1. Publish the app and then install it via the app.

**I'm happy to hear any feedback or questions on this. I hope you all enjoy it.**
