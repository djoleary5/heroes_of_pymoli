# heroes_of_pymoli

The task is to analyze data from an independent gaming company's most recent fantasy game, Heroes of Pymoli. Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. The company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

## Data
A set of poll data called [purchase_data.csv](election_results/Resources/purchase_data.csv), which is composed of seven columns: `Purchase ID`, `SN`, `Age`, `Gender`, `Item ID`, `Item Name`, and `Price`.

## Steps Taken
* Calculated the total number of players. `There are 576 unique players.`
* Calculated the number of unique items, average purchase price, total number of purchases, and total revenue then organized them into a dataframe `totals`.
* Created a dataframe of gender demographic data `genderCount` that includes percentage and count of male, female, and other/non-disclosed players who made in-game purchases.
* Created a dataframe `genAn` of purchasing analysis broken down by gender that includes the purchase count, average purchase price, total purchase value and average purchase total per person.
* Created a dataframe `ageGrp` of purchasing data that includes the purchase count, average purchase price, total purchase value and average purchase total per person broken down by age groups `<10`, `10-14`, `15-19`, `20-24`, `25-29`, `30-34`, `35-39`, `40+`.
* Identified the top spenders by creating a dataframe `spendGrp` that included the purchase count, average purchase price, and total purchase value for each player.
* Identified the most purchased items by creating a dataframe `popGrpAa` that includes the `Item ID`, `Item Name`, purchase count, item price, and total purchase value for each item, sorted by purchase count.
* Identified the most profitable items (by total purchase value) by creating a dataframe `popGrpB` that includes the `Item ID`, `Item Name`, purchase count, item price, and total purchase value for each item, sorted by total purchase value.

## Observations
* The vast majority of players are male (84%) but female and other/non-disclosed players spent more per person, 4.47 & 4.56 respectively versus 4.07 for males.
* A majority of players fall into the 20-24 age bracket though the age bracket that spent the most per person is 35-39 at 4.76 per player.
* The most popular item is also the most profitable, 'Oathbreaker, Last Hope of the Breaking Storm'.
