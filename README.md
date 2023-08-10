# J124 Intro to Data Journalism Final Project: A Data-Driven Look Into The Baseball Hall of Fame
## By Kyle Ngo
Open and make your own personal copy of the [database](https://docs.google.com/spreadsheets/d/1PE7dACChPplbgefL6Vqhv6HwqOJ9SEG_7OUa4KmGCnI/edit?usp=sharing). <br/>

### Data Analysis
#### 1. Out of those in the dataset, who had the highest OPS, the lowest OPS, and the median OPS?
1. CLick the Filter button and click the three lines next to OPS in column AC.
2. Sort A->Z to find the lowest OPS, who should be Luis Aparicio with a 0.653.
3. Sort Z->A to find the highest OPS, who should be Josh Gibson with a 1.176.
4. With the column AC selected, go to the Data tab -> Column Stats -> Median. The median should be 0.8405, which is right in between three players: Carl Yastrzemski and Cap Anson with a 0.841, and Cool Papa Bell with a 0.840.

#### 2. What were the top three most common values of OPS and WAR/pos?
1. Create a Pivot Table (Insert -> Pivot Table) encompassing the entire spreadsheet.
2. Put OPS as rows, Name as values.
3. Under the OPS box in rows, change "sort by" from "OPS" to "COUNTA of Name" and change "order" to Descending.
4. The top three most common values of OPS should be 0.817, 0.846, and 0.797.
5. Do the same for WAR/pos, just with all instances of OPS being replaced by WAR/pos.
6. The most common value of WAR/pos is a four-way tie between 68.4, 59.5, 48, and 47.7.

#### 3. How does the average WAR/pos per year for those inducted in the 1990s (1990-1999) compare to those inducted in the 2000s (2000-2009) and those inducted in the 2010s (2010-2019)?
1. Create a new Pivot Table.
2. Put Inducted as rows, WAR/pos as values.
3. Add up the total WAR/pos values for each year in the 90s (1990-1999). This should equal 991.3.
4. Divide by 10 to get an average WAR/pos per year of 99.13 in the 90s.
5. Do the same for the 2000s. The total WAR/pos for the decade should be 1,370.3.
6. Dividing by 10 should give an average WAR/pos per year of 137.03 for the 2000s decade.
7. Do the same for the 2010s. The total WAR/pos for the decade should be 1272.2.
8. Dividing by 10 should give an average WAR/pos per year of 127.22 for the 2010s decade.
9. Based on this, we can see that the inductees in the 90s had a much lower average WAR/pos than the inductees in either the 2000s or the 2010s. This could possibly indicate that much better players got inducted after 2000, or that simply not as many players in general made it in 90s compared to the 2000s or 2010s.

#### 4. What is the percent change in average ASGs per year from the 2000s inductees to the 2010s inductees?
1. Create a new Pivot Table
2. Put Inducted as rows, ASG as values.
3. Add up the total number of ASGs in from 2000-2009 and 2010-2019, which should give you 199 and 153.
4. Divide each value by 10 to give you a 19.9 average ASGs per year for the 2000s and 15.3 average ASGs per year for the 2010s.
5. Then, do (New - Old) / New, or (15.3-19.9)/15.3, times 100, to give a percent change of 30.07%.

#### 5. Find the mathematical average of every statistical column.
1. Go to Data -> Column Stats.
2. Scroll to find "Average."
3. Record this value for each column, besides Rk, Name, Inducted, From, and To.
4. The row should have these values. <br/>

| Yrs   | ASG  | WAR/pos | G    | PA   | AB   | R    | H    | 2B  | 3B | HR  | RBI  | SB  | CS | BB  | SO  | IBB | GDP | SF | SH | BA    | OBP   | SLG   | OPS   |
|-------|------|---------|------|------|------|------|------|-----|----|-----|------|-----|----|-----|-----|-----|-----|----|----|-------|-------|-------|-------|
| 17.93 | 6.21 | 63.03   | 2046 | 8603 | 7551 | 1267 | 2283 | 395 | 98 | 217 | 1176 | 210 | 70 | 870 | 781 | 90  | 147 | 67 | 93 | 0.304 | 0.378 | 0.469 | 0.847 |

### The Pitch








### Data Visualization
This [data visualization](https://www.datawrapper.de/_/B1qrO/) is a scatterplot comparing the WAR on the y-axis to the OPS on the x-axis for all of the position players in the Hall of Fame. Average lines are at 60 WAR and 0.850 OPS. <br/>
![Scatterplot comparing the WAR on the y-axis to the OPS on the x-axis for all of the position players in the Hall of Fame](https://github.com/kylengo32/j124final/assets/140004465/165409ac-4f12-48a3-b5a5-8053307f830b)

### Possible Interviewees
#### Jon Heyman
Jon Heyman is on the committee that votes to induct players in the Baseball Hall of Fame. Heyman is also a prominent baseball journalist, serving as a for the New York Post and an MLB insider with MLB Network. Heyman would have great insight into how he and his colleagues evaluate their ballot of potential Hall of Fame inductees, along with what type of stats or circumstances they consider.
* https://twitter.com/jonheyman
* jonhheyman@aol.com
#### Steve Hirdt
Steve Hirdt is the Executive Vice President of the Elias Sports Bureau and the Senior Director of Operations and Research at Stats Perform. Steve is also a voter for the baseball hall of fame, specifically on the subcommittee, the Contemporary Baseball Era Committee, which votes on players who have been retired for 15+ years and missed the Hall of Fame on the normal ballot. With Steve’s highly statistically-minded background and outlook on his voting, he would be a great person to talk to about his insight on what type of stats and baselines he uses to choose hall of famers.
* https://twitter.com/stevehirdt?lang=en

### Two Additional Sources
* This [FiveThirtyEight article](https://fivethirtyeight.com/features/paul-goldschmidt-is-on-his-way-to-the-mvp-and-maybe-even-the-hall-of-fame/) discusses one current player, Paul Goldschmidt, and his chances of making it into the Hall of Fame as he enters the twilight of his career. It uses some more in-depth statistics to analyze his odds, and would be a good additional source to get extra types of data and analysis from.
* This [____
