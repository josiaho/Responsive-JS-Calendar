##Responsive Javascript JSON Calendar
* Automatically toggles between Calendar & List views based on screen size
* Add Titles, Links & Notes via JSON
* Small, Vanilla, and Easy to Customize

===
###Basic
Gets current month & year:

	makeCalendar()
	
###Custom Month/Year
	makeCalendar(month, year)
	
	// January, 2014
	makeCalendar(1, 2014)


###Add JSON Events
    var events = {
        "2013-12-25":[
        	{"title":"Christmas Party","link":"#","notes":"Bring Cookies!"}
        ],
        "2014-1-1":[
        	{"title":"New Year's Day","link":"","notes":""},
        	{"title":"Dinner @ Smith's","link":"","notes":"5pm"}
        ]
    };
    
    makeCalendar(1, 2014, events); // Month, Year, Event JSON

