# HA-DateTimePicker
A date and time picker with Solar(Persian) and Gregorian calendars

##View [Demo](http://demos.hosseinalipour.ir/ha-datetimepicker)

# Installation

Just download the files and and include JS, CSS and other resource files in your project

# How to use

## - Add *data-ha-datetimepicker* attribute to your DOMElement

```
  <input type="text" id="datetime" data-ha-datetimepicker="#datetime" />
```

## - Show using Javascript

  ```javascript
  var dp = new HaDateTimePicker("#datetime");
  dp.show();
  ```
  
#Features
You can initiate your HA-DateTimePicker with this set of options:
*Note: your can use with javascript object or HTML Attribute*

Javascript option | HTML attribute | Type | description
------------ | ------------- | ------------- | -------------
date | data-ha-dp-date | Date | Initial month and year sheet
selectedDate | data-ha-dp-selecteddate | Date | Selected Date
minYear | data-ha-dp-minyear | Number | The first year in the year dropdown list
maxYear | data-ha-dp-maxyear | Number | The last year in the year dropdown list
isSolar | data-ha-dp-issolar | Boolean | Turns into Solar(Persian) Calendar
resultInSolar | data-ha-dp-resultinsolar | Boolean | Returns the result in Solar(Persian) date mode
forceSetTime | data-ha-dp-forcesettime | Boolean | Forces the user to set the time
disableTime | data-ha-dp-disabletime | Boolean | Disables the time feature
pagingDuration | data-ha-dp-pagingduration | Number | The duration time of changing month (In Miliseconds)




***
Copyright © 2016 by [Hossein Alipour](http://hosseinalipour.ir)

