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

To install:

1. download and unzip the plugin.
2. Copy it to your plugins directory. Make sure it's world-readable.
3. Modify a head or foot file to include $calendar::calendar, $calendar::month_calendar or $calendar::year_calendar
4. Try it out — load your blog in your browser. If you see a calendar, great!
5. Look at your error log. Verify you have an 'enabled' line.
6. If you're wanting to verify caching is working, load the page again, and now look for an error log line "calendar debug 1: Using cached state"
7. Once you're satisfied it's working, edit the $debug_level configuration variable to 0. There are a couple other configuration variables you may wish to change, too.
8. Drop me a note to let me know you're using it; if you're having problems, let me know and I might be able to help. If everything's working okay, please let me know that, too.

[notes]: https://web.archive.org/web/20080225044801/http://molelog.molehill.org/blox/Computers/Internet/Web/Blosxom/Plugins/Calendar/calendar-0-6i.writeback

## License
This license is reprinted here for convenience; the actual license is contained in the `calendar` file at the bottom.

```
LICENSE
this Blosxom Plug-in
Copyright 2003, Todd Larason

(This license is the same as Blosxom's)

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
```
