---
name: "Said Mirza Unsu"
slack_handle: "@U07E4UHB64E"
github_handle: "@8Mirza8"
tutorial:
---

# Solar Powered Business Card

<!-- Describe your board in 2-3 sentences. What are you making? What will it do? -->
I designed a business card that charges the supercapacitors on it in a sunny environment and illuminates itself by turning on the light when it is dark.
<!-- How much is it going to cost? -->
It will be around 77 dollars because I couldn't find all the parts in the basic catalog and I had to get some parts from the extended library. I couldn't even find the solar panel and super capacitor so I'll find and install them myself.
<!-- Tell us a little bit about your design process. What were some challenges? What helped? ***Totally optional*** -->
It would be quite challenging to store enough energy to light a LED at full power for a few minutes with a small solar panel and super capacitors, so I designed a circuit with a ne555 that would turn the LED on and off at approximately 60% capacity at certain intervals. In this way, the LED would light up for a longer time. At the same time, the solar panel I wanted to use provides 1.5 volts of output, while the super capacitors charge with 5.5 volts, so I made a charging circuit with MT3608 in this part.
