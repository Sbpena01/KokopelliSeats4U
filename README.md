# KokopelliSeats4U
This is Team Kokopelli's deliverables for our final project in CS3733 Software Engineering. The application is an AWS hosted website that allows for users to create venues and shows for customers to find and purchase tickets.


Our team consisted of 3 members, we were exempted from needing to implement blocks and the functionality related to it

You must be logged in for most of the functions in the websites to work. This is due to the application keeping track of which venue manager has authority over which venue.

Please create new accounts before grading by selecting the “Create Account” button on the log in screen.
You are able to create an account of any type.

Make sure the usernames are unique. Passwords can be as simple as 123.

The Time is in EST

As a consumer when searching for venues the name of the venue will not show up but the shows inside of the venue will show up.

If nothing happens, click the button again, sometimes the button updates slowly

In some situations, such as creating a show, the action can be verified through generating a show report or requesting to list shows/venues, not pop up.

If you are partially searching for a show, the search needs to have complete words.

To search for “Just Added”, inputting “Just” or “Added” will work, but not “Ju”

Venues can’t have the same name.

When “selecting” a show to perform an action, you need to input the name and the date (the later should be displayed in the UI in EST and military time)

You will need to translate, military time to AM and PM when inputting into the field

When displaying the date of a show or venue, the format is yyyy-mm-dd hh-mm-ss. There are some added characters like Y and Z. We do not know what these mean but the date information is still displayed correctly.

These are the points we missed in previous iterations:
#1 - Venues don’t have credentials (lost 1 point)
#1 - Start new browser and try to have Venue manager for Wobegon Public High School try to load up its information (lost 2 points)
#1 - Admin logs in (lost 5 points)
#1 - Start new browser and try to have Venue manager for Wobegon Public High School try to load up its information (lost 2 points)
#2 - In another browser as the VM for Worcester Tech try to load the list of shows (lost 5 points)
#2 - Venue Manager for Worcester Tech Generate Shows Report for their own venue, which should only contain two shows (it is acceptable to just list the names of the shows in venue) (lost 5 points)
