# stock-analysis
Green Energy VBA Stock Analysis
Purpose

The project aimed to cut down the time it takes to apply a variety of analysis tools to multiple different companies and their stock index. Refactoring showed a significant reduction in the amount of time it took to run the code.


Analysis and Challenges


- Prepare our dataser `VBA_Challenge.vbs` file for the project.
- Create our resources folder in **GitHub** to hold the run-time pop-up messages that we’ll screenshot after running refactored analyses for 2017 and 2018.
- Create and convert our `XLSM` file from `*.vbs` dataset that you used in this module as `VBA_Challenge.xlsm`.
- Add the VBA_Challenge.vbs script to the Microsoft Visual Basic editor.
- Use the steps **Refactor VBA code and measure performance** to add code where indicated by the numbered comments in the starter code file.

Our Challenge Data Background

Steve had the dataset, but we needed to help him run multiple looped analysis on it. While our code pattern was sound, it was still uncertain how long it would take.

Once the logical structure of the code was assembled, we began by keeping in mind that the code should be clean and flow logically.



RESULTS: Refactor VBA Code and Measure Performance
Deliverable Requirements, Code Examples, Compare Stock Performance and Timestamp procedure below:
1. The tickerIndex is set equal to zero before looping over the rows.

tickerIndex variable and set it equal to zero 
access the correct index across the four different arrays on VBA Code 

2. Arrays are created for tickers

- Created output arrays: 
- tickerVolumes, long data
- tickerStartingPrices, single
- tickerEndingPrices, single


3. Used ticketindex to access first and last rows

Set ticker volume to zero

4. Code captured the follwing data: 
- tickers, 
- tickerVolumes, 
- tickerStartingPrices, 
- tickerEndingPrices.

Added the ticker volume for the stock ticker in focus.
Stored values

Used if-then statements to confirm first or last row

5. Code is successful

- Associated positive result with green
- Associated negative results with red


6. There are comments to explain the purpose of the code.

Readability was a major target,

Commenting & Documentation,
Consistentancy in using whitespaces
All comments were correctly ignored
Code was a little long

Compared the output of our allstocksanalysis to the one provided by the modules and confirmed accuracy.


SUMMARY

1. Advantages and disadvantages?

more logical and efficient code is very possible and much easier to understand; confirmed readbility is important.

Disadvantages:

VBA skillset is weak as it is not frequently used. Spent a lot of time going back over the code.

2. What can I do better?

Keeping in mind the pattern of the code and the general pattern is important as it is more closely aligned with problem-solving. If you lose track of the problem due to messy coding, you may end up addressing something that the client did not need.

