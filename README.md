angular-moment
==============

Wrapper for moment.js


* add 
```javascript
moment("2014-11-24T05:45:00Z").add('days', 5).calendar()
```
```html
<p> "2014-11-24T05:45:00Z" | momentAdd:'days':5 | momentCalendar </p>
```
output: 11/29/2014

* calendar
```javascript
moment("2014-11-24T05:45:00Z").calendar();
```
```html
<p> "2014-11-24T05:45:00Z" | momentCalendar </p>
```
output: 11/24/2014

* day
```javascript
moment("2014-11-24T05:45:00Z").day("2014-11-29T05:45:00Z");
```
```html
<p>"2014-12-27T05:45:00Z" | momentDay</p>
```
output: 6

* dayOfYear
```javascript
moment("2014-02-24T05:45:00Z").dayOfYear();
```
```html
<p>"2014-02-24T05:45:00Z" | momentDayOfYear</p>
```
output: 55

* diff
```javascript
moment("2014-11-24T05:45:00Z").diff("2014-11-29T05:45:00Z");
```
```html
<p>"2014-11-24T05:45:00Z" | momentDiff:"2014-11-29T05:45:00Z"</p>
```
output: -432000000

* daysInMonth
```javascript
moment("2012-02").daysInMonth();
```
```html
<p>"2012-02" | momentDaysInMonth</p>
```
output: 29

* enOf
```javascript
moment().endOf("week");
```
```html
<p>"week" | momentEndOf</p>
```
output: "2014-05-25T02:59:59.999Z"

* toJSON
```javascript
moment().toJSON();
```
```html
<p>"2014-11-24" | momentToJSON</p>
```
output: 2014-11-24T03:00:00.000Z

* format
```javascript
moment().format("dddd, MMMM Do YYYY, h:mm:ss a");
```
```html
<p>"2014-11-24T05:45:00Z" | momentFormat:"dddd, MMMM Do YYYY, h:mm:ss a"</p>
```
output: Monday, November 24th 2014, 2:45:00 am