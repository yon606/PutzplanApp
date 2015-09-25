# PutzplanApp

##How it works...
Is an interactive game that rewards users with points for cleaning.
Everytime a memeber of a commune cleans up a certain part or item of the flat, he adds it to his list.
Depending on the integrated reward system, he gets a certain amount of points.(and archievments)
Now the members have to keep up with the current highscore of their flatmates. 
You'll be able to share your progress on facebook and activate a function that auto-posts huge differences between the members of the flat depending on preset parameters (timeSinceLastCleanup, pointDifference(availability))
There will be push notifications aswell that remind you of your mates highscore and of the dirt-status of you flat.(e.g. 1 week reminder to clean the toilet)

##Technical dependencies
* HTML and CSS interface
* JavaScript functionality
* MySql Database

##Features
### Basic
* Save what a user has cleaned up including:
  * itemName or roomName (choosen from list)
  * photo(before and after)
* Edit the list of cleaned items
* View the status of your flat (what has been cleaned last? whats urgent?)
* See your profile and your mates profiles including
  * last cleanup (time, item)
  * timeline score, highscore, streak
  * fauxpas counter (amount of missed cleaning sessions === difference between scores was too high)
  * archievments
 
### Presets
* Add items and rooms to your flat template (to populate list for itemName and roomName)
  * calculate points for every single item or room by appending attributes to them.(nastiness,timeConsumptionCleaning,ownership(all,me,notme))
  * cleaning intervall (how long does it take to get dirty in general ?)
  * 

### Social
* Share your progress
* Share point difference between memebers of the flat
* Share archievments

### Design
