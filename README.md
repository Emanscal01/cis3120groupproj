# cis3120groupproj
it works now lmao

*** Important Variables ***

"combined" pandas data frame, variable has the daily prices for a given stock and the SPY in descending order with dates

"combinedPC" pandas data frame, variable has the daily percent changes for a given stock and the SPY in descending order with dates

"ticker" string, variable is the ticker inputted by user, is all uppercase, may have numbers

"datenums" integer list, a list of integer numbers, are indexes that correspond to the first day of each month with available data, can be used for x-axis labels on graphs by using: GraphName.set(xticks = datenums)

"combinedStats" pandas data frame, contains float statistical data for both the asset and SPY closing prices
