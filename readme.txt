Hi Dr. Wilkerson!

I am writing to let you know that I created an interactive map website to answer the question, "What areas in Texas are far away from the nearest SNAP retailers?" The link for the website is kiron-ang.github.io/SNAPmapTX. An interactive map is the best approach for exposing areas with few SNAP locations, because by highlighting points based on where users click, it allows users to investigate on their own and make quick comparisons. I filtered the CSV file provided to keep only rows with Texas addresses.

By plotting the features "X" and "Y" with the D3 library, I noticed that, thanks to the large size of the dataset, a dilated shape of Texas had formed. I removed three outliers with incorrect "X" and "Y" information that were outside the confines of Texas: Dime Box Grocery in Dime Box, TX; DOLLAR GENERAL 0353 in Madison, TX; and Dollar General 15022 in China, TX. Then, by setting both of the scales to confine themselves in a square, I created a recognizably Texas shape; this is true on any screen, including a phone.

After changing the colors to match a Pantone color palette, I centered the shape of Texas on the screen. The final and most challenging step was adding the interaction. I settled on allowing users to click within the axes, triggering distance calculations and sorting so that only the ten closest SNAP retailers were shown. I know this is not an obvious approach for exposing areas that do not have adequate SNAP location coverage, but I believe it has its merits: With the knowledge that ten points will always be highlighted, users can compare the distance of the ten points to determine whether or not the area is sparsely dotted with SNAP retailers.

Thank you for your time and evaluation.

Sincerely,

Kiron Ang