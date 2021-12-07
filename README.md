# ReactCalculator
A calculator built on React following Kyle's tutorial (https://www.youtube.com/watch?v=DgRrrOt0Vr8&t=72s&ab_channel=WebDevSimplified) from WebDevSimplified

However I made a few changes in order for the calculator to work. 


I added "state" in front of currentOperand when creating ADD.DIGIT case. This should look like this:

And another bug I noticed while playing with the calculator and testing it, is that the app would crash when pressing "." with no digits there. 

This can be easily solved by adding the following line on top of the other If statement you have for the "." case on payload digit:

Also I checked that all the calculators I have when pressing AC a "0" is displayed, so I added that feature
      
I also incorporated a DarkMode toggler as an extra feature of the app. 
