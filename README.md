# Feed Reader Testing Website

## Table of Contents
	web-based application that reads RSS feeds.
	jasmine library.
## Instructions
	###Open index.html.
	###press End to go to the end of the page to see jasmine and what it can do.
	###if you see red bar! that means there is a test is failled or erorr in the code.
	### 7 specs ,0 failures that mean the code checked 7 functions and all of them are right,,if there any wrong you would see it and the line of the failure.
	###you can make sure of the success in this way.
		####chek the circles under Jasmine Logo when it completes that means test isn`t wrong and you can go to every circle to know what it`s refer to.
	### or you can in this way
		####From the string in the footer of page as i made this.
			##### if allFeeds variable has been defined and that it is not empty you will see "are defined" in under "RSS Feeds" section.
			##### if each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty you will see "The URL in it is  defined" under "RSS Feeds" section.
			##### if each feed in the allFeeds object and ensures it has a name defined and that the name is not empty you will see "The name in it is defined".
			##### if the menu element is hidden by default you will see "the element is hidden by defaut" under "the menu" section.
         	##### if  the menu changes visibility when the menu icon is clicked you will see "the visibility  will change when the menu icon is clicked" under "the menu" section.
			##### if  the loadFeed function is called and completes its work, there is at least a single entry element within the feed container you will see "The feed container at least single entry element" under "Initial Entries" section.
			##### if a new feed is loaded by the loadFeed function that the content actually changes you will see "it is different from the old feed" under "New Feed Selection" section.
