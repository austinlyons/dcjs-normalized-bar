dcjs-normalized-bar
===================
[See the demo here](http://www.seeaustinhack.com/dcjs-normalized-bar/)

This demo uses dc.js stacked bar chart to create the appearance of a normalized bar chart. 

It turns this data:

```
var data = [
  {date: "2014-09-01T8:00:00Z", courses: ["Biology", "Math"]},
  {date: "2014-09-01T9:00:00Z", courses: ["Math", "Physics"]},
  {date: "2014-09-01T10:00:00Z", courses: ["English"]},
  {date: "2014-09-01T11:00:00Z", courses: ["Biology"]},
  {date: "2014-09-01T12:00:00Z", courses: ["English", "Math", "Physics"]},
  {date: "2014-09-01T13:00:00Z", courses: ["Accounting", "Biology"]},
  {date: "2014-09-01T14:00:00Z", courses: ["Physics"]},
  {date: "2014-09-01T15:00:00Z", courses: ["Math"]}
];
```

into this interactive chart ([demo](http://www.seeaustinhack.com/dcjs-normalized-bar/)):

![screenshot of demo](http://i.imgur.com/IbxZxj6.png)

If you change the data, the chart updates as expected. Let's add accounting to the 8AM time slot:

```
var data = [
  {date: "2014-09-01T8:00:00Z", courses: ["Biology", "Math", "Accounting"]},
  {date: "2014-09-01T9:00:00Z", courses: ["Math", "Physics"]},
  {date: "2014-09-01T10:00:00Z", courses: ["English"]},
  {date: "2014-09-01T11:00:00Z", courses: ["Biology"]},
  {date: "2014-09-01T12:00:00Z", courses: ["English", "Math", "Physics"]},
  {date: "2014-09-01T13:00:00Z", courses: ["Accounting", "Biology"]},
  {date: "2014-09-01T14:00:00Z", courses: ["Physics"]},
  {date: "2014-09-01T15:00:00Z", courses: ["Math"]}
];
```

and we get:

![screenshot of updated demo](http://i.imgur.com/BhF0j6y.png)
