# blosxom-calendar
"Calendar" plugin for Blosxom, originally by Todd Larason

## Basic Info
The following description accompanied the plugin in the "Blosxom
Plug-In Registry":

```
calendar
Title: calendar
Description: builds a classic weblog calendar with days linked to archived postings
Configuration:
Additional Bits Required:
Author: Todd Larason
URL: http://molelog.molehill.org/blox/Computers/Internet/Web/Blosxom/Calendar/calendar-0-1i.html
Category: /calendar
```

## Usage Notes
(Usage notes are taken from [this Archived page][notes].)

This builds a calendar display of the current month. Days with
articles are links to that day's archive page; days without articles
aren't links.

1. download it, and rename it "calendar"

2. Stick it in your blosxoms plugin directory

3. Look at the configuration variables; there's probably not anything
you'll want to fiddle with, though.

4. Add "$calendar::calendar" to your head.$flavour or tail.$flavour
file. Maybe add some things to your stylesheet

[notes]: https://web.archive.org/web/20090201050817/http://molelog.molehill.org/blox/Computers/Internet/Web/Blosxom/Calendar/calendar-0-1i.html

## License
Per the original documentation, it is distributed under the [Creative
Commons ShareAlike 1.0][sa1] license.

[sa1]: https://creativecommons.org/licenses/sa/1.0/
