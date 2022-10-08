# HadrianDeveloper.github.io
A list of HTML/CSS practice projects, based on CodeCademy and GA lessons

TERMS:
    -Cruft: code that is not being used
    -redundant images will slow performance
    -vendor prefixes: codes to talk to all major browsers. Keep no-prefixes in to future proof!
        background: -webkit-linear-gradient...  <--for chrome, safari, opera
                    -moz-                       <-- for firefox
                                                NOT FOR IE/EDGE YET?
    -graceful degradation - concept where older browsers shouldnt be punished:
        eg for IE, put background: black; above the newAge code to fall back on!




CSS markup
    background: color OR url("");
    background-size: cover (stops tiling)


https://necolas.github.io/normalize.css/ <-- makes all browsers render the same!

HEADER tools
    <ul> for menu; 
    padding: 10px (all sides) to center on pg
    padding: to space out items in list

MAIN
    wrap h2 and texts into <article>
    

RESPONSIVE DESIGN
    - margin: a auto; <-- to center an object in a pg
    - use max-width
    - @media(max-width: 500px) {
        body {
            color: red;
        }
    }

COLOR CODES
    Hex color code syntax:
        #f00 = red
        #000 = black
        #FFF = white 
        trigger > level of red (F=max) > green > blue
    RGBA() syntax (with alpha)
        color: rgba(0,0,0,0.5) = opaq black background
        rgba(255,255,255,1) = white

FORMS
    <button>Like</button>

JAVASCRIPT
    Browsers fire off 'events' each time we do something; click, hover, scroll, etc. JS can 'listen' to these events and take action. Eg listen for a click event on a button element.

POSITIONING
    margin: 0 auto

float: right;  --for floating img or txt to a specific area and have text wrap around it like in newspapers