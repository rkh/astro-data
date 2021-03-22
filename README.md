This repository contains pre-calculated or recorded values for:

* **Moon phases from the year 4000 BCE to the year 2999 CE.** Values from 1700 CE to to 2082 CE have a one second precision, other values are assumed to have a 30 second precision. Note that this is much more precise than most moon phase calculators out there (which usually have a precision of 14 to 15 hours, which is enough to display the approximate moon phase, but not enough for calendar conversion, as it can lead to off by one errors). Data is grouped in one file per century named after the first two digits of each year prefixed by a minus for BCE years and a 0 for CE years (ie, data for the year 2021 is found in [moon/020.tsv](data/moon/020.tsv)).
* **Solstice and equinox data** for the years 1140 to 2999 CE. This data should have precision of a minute or better. Data is kept in [a single file](data/sun.tsv).

Years and phases are ASCII formatted integers, dates and times are ISO 8601 formatted (without timezone, which is UTC for all values).
Files are tab separated and should be very easy to parse (first line includes headers and can be discarded, subsequent lines can be split on tab character).

This data is considered public domain.
