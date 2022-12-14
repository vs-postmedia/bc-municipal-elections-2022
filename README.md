# bc-municipal-elections-2022
Geographic and vote result data from B.C.’s 2022 municipal elections – polling station locations, voting districts, etc. This is b

## NOTES ##

### VANCOUVER 
Thanks to Justin McElroy ([@j_mcelroy](https://twitter.com/j_mcelroy)) for (manually!!!) geolocating Vancouver polling stations the night poll-level results were released. 

NOTE: There are multiple division IDs associated with three polling stations in Vancouver:
 * Britannia Community Services Centre 
 * Marpole
 * RayCam Co

 You will need to filter/tally results associated with duplicate polling stations accordingly.

 Election results are available from CoV [open data portal](https://opendata.vancouver.ca/explore/dataset/municipal-election-results/table/?sort=-election)

### SURREY
There are three values assocaited with `vote_type`:
 * ADV: Advanced voting
 * GV: General voting
 * MAIL: Mail-in votes

There are multiple precinct IDs associated with several polling stations in Surrey (marked with an A/B suffix):
 * Cloverdale Recreation Centre
 * Fleetwood Community Centre
 * Guildford Recreation Centre
 * Queen Elizabeth Secondary
 * Semiahmoo Secondary

 You will need to filter/tally results associated with duplicate polling stations accordingly.

Vote results from [this HTML page](https://apps.surrey.ca/2022Results/Election%20Results%20per%20Voting%20Opportunity.html) have been converted to csv.


### OTHERS
Make a pull request & we’ll see...