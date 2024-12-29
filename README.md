# AiStartpage

This is a fork of [Forbidden-startpage](https://github.com/AmeerMoustafa/Forbidden-startpage). I adapted it to my personal preferences and use cases. It still has all the same features, I just commented out most of the original themses and kept a single one. Aditionally, I added some features from [this](https://github.com/Jaredk3nt/homepage) startpage, mainly the searchbar function, which can be activated by pressing the spacebar.

### Features:

- Multiple Themes
- Get a random theme from the list by clicking on the image
- Localstorage support to save selected theme
- Date/Time and Weather
- Customizable styling through CSS variables

### Customize Search Engine

You can change the search engine used by the search overlay by updating the url value stored in the `searchUrl` var in `index.html` to the correct string for your engine.

Examples:

- DuckDuckGo: `https://duckduckgo.com/?q=`
- Bing: `https://www.bing.com/search?q=`

# Preview

![Hinatsuru Ai](https://github.com/garaqta/AiStartpage/blob/main/preview.gif)

### How to add weather suppot

Simply go to the config.JSON file in your config folder and paster your openweatherAPI key there.
