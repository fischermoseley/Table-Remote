# Table-Remote
## Motivation
My former high school wanted to have a room equipped with CAD workstations that could transition into normal desks when they weren't being used. Commercial products for this exist, with monitor mounts that retract into the back of the desk, but controlling a classroom full of them is cumbersome. Each one came with it's own remote that is unique to the desk, meaning that raising a room full of monitors required pushing the "up" button on 12 individual remotes. This is a problem.

# Process
By using an Adafruit Trinket M0 and an eBay 433MHz radio transciever, I was able to "record" the codes that were sent by the transmitter to raise and lower the tables. By resending these codes, the table electronics think that they're getting a signal from the actual remote, and the Trinket is able to spoof the original transmitter. The Trinket can send these codes in quick succession, allowing for a classroom worth of tables to be raised or lowered with a single button.

This whole project was built in the middle of a fire drill using parts that we had left over from some kits.

# Results
![Alt Text](https://github.com/FischerMoseley/Table-Remote/blob/master/results.gif)