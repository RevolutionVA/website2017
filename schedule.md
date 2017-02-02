
#Schedule

The schedule object is an array of events. Each event object will be either a talk, or other event (lunch, keynote, etc). 

####Talk Event
```
{
	"talk" : "howitsmade_revconf2017",
	"location": "Lynnhaven Room",
	"start" : "01-06-2017-1000"
	"end" : "01-06-2017-1050"
}
```

####Other Event

```
{
	"title" : "Lunch",
	"description" : "Turkey Burgers, Veggie Burgers, Baked Beans, Corn",
	"location": "Ball Room A",
	"start" : "01-06-2017-1200"
	"end" : "01-06-2017-1315"
}
```

The start and end times (in 24 hour format) are as follows:
```
'yyyy-mm-dd-hhmm'
```
So a session scheduled for 2:15 pm on June 1st would be:
```
'2017-06-01-1415'
```
