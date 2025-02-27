# What is Auto-Rick?
Auto-Rick is an Extension to automatically play Never gonna give you up by Rick Astley when you open youtube.

# How to use

1.Install the Tampermonkey extension for your browser from https://www.tampermonkey.net/ if you haven't already.

2.Click on the Tampermonkey icon in your browser and select "Create a new script".

3.Replace the default code with the code provided above.

4.Save the script.

5.Open YouTube to see the redirect in action.


```
// ==UserScript==
// @name         Auto Play Rickroll on YouTube
// @namespace    http://tampermonkey.net/
// @version      1.0
// @description  Automatically play "Never Gonna Give You Up" when opening YouTube
// @author       DuckSong510
// @match        *://www.youtube.com/*
// @icon         https://www.youtube.com/favicon.ico
// @grant        none
// ==/UserScript==

(function() {
    'use strict';
    const rickrollURL = 'https://www.youtube.com/watch?v=dQw4w9WgXcQ';

    // Check if we are already on the Rickroll video
    if (window.location.href !== rickrollURL) {
        window.location.replace(rickrollURL);
    }
})();
```
