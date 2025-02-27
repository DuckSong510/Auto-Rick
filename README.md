# Rickroll-prank
Extension to automatically play Never gonna give you up by Rick Astley when you open youtube.

# How to use

1.Install the Tampermonkey extension for your browser if you haven't already.

2.Click on the Tampermonkey icon in your browser and select "Create a new script".

3.Replace the default code with the code provided above.

4.Save the script.

5.Open YouTube to see the redirect in action.


```
// ==UserScript== // @name         Rickroll Redirect // @namespace    http://tampermonkey.net/ // @version      0.1 // @description  Redirect to Rick Astley's "Never Gonna Give You Up" YouTube video // @author       You // @match        *://*.youtube.com/* // @grant        none // ==/UserScript== (function() { 'use strict'; // Redirect to Rick Astley's "Never Gonna Give You Up" YouTube video window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ"; })();
```
