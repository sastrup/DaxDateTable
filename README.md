# DaxDateTable
DAX and Power BI Template to create a DAX Date Table

## Overview
* Supports major US holidays by default
    * Custom organizational or international holidays can be added or removed using the 'holidayTable' variable
    * Holiday logic was informed by SQLBI's Marco Russo's DAX table here: https://github.com/marcosqlbi
* Contains most common attributes required for a functional date dimension table
* Customizable for start/end dates as well as week start days
    * For financial dates that do not line up to calendar dates or international calendar support, Marco Russo's table mentioned above is a good option
* Helpful uncommon attributes include: 
    * Day index
    * Week index (relative to the calendar week)
    * Week index (relative to the calendar day)
    * Holiday and working day flags

