# Living Toki Pona

Living Toki Pona lets you find the meaning of life together by brining the conlang Toki Pona to life!

## Milestone goal
The goal for the first release is to be able to describe english concepts with Toki Pona to build up a idiom list for the Toki Pona language. The user input is compared to that of the community to determine what version is the best. By increasing the difficulty and starting with simple concepts the user will both learn the language Toki Pona and finds out the essence of life.

## Implementation
### UI
The UI is not based on any standard UI framework or guideline. The icons are Toki Pona Sitelen Sitelen glyphs and are new and perhaps alienating to new users. A new input style is used to input glyphs directly without resorting to inputting the romanized form of Toki Pona.

### Plugins used
**com.darktalker.cordova.screenshot** is used to be able to share Sitelen Sitelen glyphs rendered from HTML. I'm not using a canvas to render the Sitelen Sitelen but SVGs with HTML5 flex-box layout, so I can only export the image using a form of screenshotting.

**nl.x-services.plugins.socialsharing** is used to share images on social networks.

**com.lefortsoftware.ttsplugin** is a plugin that allows the use of the text-to-speech service of the phone. It is used to pronounce the Toki Pona glyphs as the app is a learning experience and users will not know how to pronounce the words. Finnish is chosen as the text-to-speech dialect because of its neutral intonation.

### Services
Right now the app is not connected to any services of back-end. But it could be linked to a site such as [https://tatoeba.org/].
