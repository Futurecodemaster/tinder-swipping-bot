# tinder-swipping-bot
This code is a script written in Python that uses the Selenium library to automate the process of logging into Tinder and swiping right (liking) on 100 profiles.
It starts by importing the necessary libraries and setting the email and password for a Facebook account that will be used to log into Tinder. The Chrome web driver is then initialized and the script navigates to the Tinder website.

Next, the script logs into Tinder using the Facebook account by clicking on the login button, selecting the Facebook login option, and entering the email and password into the Facebook login form.

After logging in, the script allows the website to access the user's location and dismisses the notifications and cookies pop-ups.

Finally, the script enters a loop that swipes right on 100 profiles. If a match occurs, it clicks on the match pop-up. If there is an error clicking the like button, it waits for 2 seconds before trying again.

The script ends by quitting the web driver.
