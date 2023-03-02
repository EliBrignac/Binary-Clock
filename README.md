# Binary-Clock

https://user-images.githubusercontent.com/94129362/222329973-20b13574-4bb4-476b-a59f-899bc0b5754e.mp4


Demo ^



How to compile and run the code:

Type into the terminal `make run` and the clock will start ticking

To toggle between modes, enter a new terminal window and run the command
`ps -U <UDID>` UDID is the thing at the begining of ur UD email.

Then look from the list that gets displayed, look for the one that says _"clock"_ Then from the displayed column look at the number 4-5 digit number that is displayed in the same row as the "clock"

Then write the command:
`kill -usr1 <4-5digitNum>` this 4-5digitNum is the same one that was displayed in the previous step.

Your clock will now be toggled to the new mode if the time of day is past 12pm. Repeat the steps and send the same command to change the clock back to normal. 
