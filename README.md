# MMM-TamilCalendar
# Based on MMM-HTMLBox

The Tamil daily calendar site has images for every day of the current and previous years.

https://www.tamildailycalendar.com/

Their image filenaming convention for current day is "date + 2 digit month + 4 digit year".

This page will break if anything changes

## Installation
```shell
cd <your MagicMirror Directory>/modules
git clone https://github.com/rabisamuel/MMM-TamilCalendar
```

## Configuration
```javascript
{
  module: "MMM-TamilCalendar",
  position:"bottom_bar",
  config: {
    width: "100%",
    height: "200px",
    refresh_interval_sec: 3600,
    content: "There is nothing to display. <br>Put your HTML code into content field in 'config.js'.",
    file: "tamilcalendar.html", //Relative path from `MMM-TamilCalendar`
  }
},
```