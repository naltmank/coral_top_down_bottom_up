# coral_top_down_bottom_up
Contains data and code for Altman-Kurosaki and Hay 2024 MEPS

# Data
The data folder contains four files:

algal_overgrowth.csv contains data on the amount of algal overgrowth, mortality extending beyond regions of overgrowth, and the combination of the two for corals. These data were calculated by taking the pictures of the front and back of each coral fragment and calculating the area of overgrowth/mortality relative to the planar area of the coral in the photo in imageJ.

coral_growth.csv contains data on the net growth of corals over the course of the 34-d experiment, calculated as the % change in wet weight.

corallivory_data.csv contains data on the amount of coral predation on A. pulchra and P. rus over the three filming periods (weeks 0, 2, 4). Only weeks 2 and 4 were used in analyses. Fish code and Fish spp. refer to the species of fish we obersved taking bites and TOTAL refers to the total amount of bites observed on a given coral in a given video. Only TOTAL bites were used in the final models.

herbivory_data.csv contains data on the amount of herbivory observed in the videos (see above and the methods section of the publication for details on timing). The Acropora base and Porites base refer to the amount of bites taken on the plastic bases holding our Acropora and Porites fragments, but these were much more rare than the number of bites taken on the cinderblock so all values were combined for analyses. Fish code and fish species as above in the corallivory data.

# Code
All code for analyses and production of figures can be found in the coral_top_down_bottom_up_code.Rmd file.
