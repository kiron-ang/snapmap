Hi Dr. Wilkerson!

I am writing to let you know that I created an interactive map website to answer the question, "What areas in Texas are far away from the nearest SNAP retailers?" The link for the website is kiron-ang.github.io/SNAPmapTX. An interactive map is the best approach for this question, because by highlighting points based on where users click, it allows users to investigate on their own and make quick comparisons. I filtered the CSV file provided to keep only rows with Texas addresses.

By plotting the features "X" and "Y" with the D3 library, I noticed that, thanks to the large size of the dataset, a dilated shape of Texas had formed. I removed three outliers with incorrect "X" and "Y" information that were outside the confines of Texas: Dime Box Grocery in Dime Box, TX; DOLLAR GENERAL 0353 in Madison, TX; and Dollar General 15022 in China, TX. Then, by setting both of the scales to confine themselves in a square, I created a recognizably Texas shape; this is true on any screen, including a phone.

After changing the colors to match a Pantone color palette, I centered the shape of Texas on the screen. The final and most challenging step was adding the interaction.

Thank you for your time and evaluation.

Sincerely,

Kiron Ang