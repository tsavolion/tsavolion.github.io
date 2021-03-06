Un-Gerrymandering:

Like many Americans, the results on election night took me by surprise. Nearly all the polls and pundits were wrong. The Democrats' stunning defeat (and Clinton's substantial popular vote lead) has resurrected an age old debate about the Electoral College.

Personally, I believe the Electoral College plays an important role in protecting the rights of smaller states from being violated by more populous regions. That's not to say that I don't recognize major flaws in the system.

Gerrymandering is the act of manipulating the boundaries of electoral districts for the purpose of benefitting one's own party. The term was named after Governor Elbridge Gerry of Massachusetts who manipulated the voting districts in his state to strengthen his party's dominance. Apparently one such district resembled a salamander, hence Gerrymandering.



![](https://tsavolion.github.io/capstone_images/gerry.png)



The problem is not in the Electoral College, but rather in the way districts have been corrupted. The solution is simple: redraw voting districts to be representative of the state so voters from each party are fairly represented.

For this project, I have chosen to focus specifically on Pennsylvania. Pennsylvania is a battleground state (even though most Democrats thought it was safely in the basket). It was an incredibly close race, as according to the popular vote it was 48.8% for Trump and 48.6% for Clinton. But, had you judged judged the outcome solely from county map, it looked like a Republican blow-out.



![](https://tsavolion.github.io/capstone_images/gerry2.png)



Let's explain this. Nearly 6 million Pennsylvanians cast their vote on Monday November 7th, 2016, and Donald Trump only beat Hillary by 100,000 votes.

This plot shows county by county how Trump and Clinton performed. One pattern that can be observed here is that Hillary Clinton performed far better than Donald Trump in counties with larger populations but the left side of the plot, where the less populated Counties are, Trump consistently did better than Hillary but by a smaller margin.



![](https://tsavolion.github.io/capstone_images/countybycounty16.png)



Four years ago, the Democrats had more success in Pennsylvania as the state's Electoral votes went to Barack Obama. Using the same county by county comparison as above (removing third party candidates) we see that much like this election the Democrats did substantially better in highly populated counties, but unlike Hillary Clinton, Barack Obama was able to win in some of the medium-sized counties.



![](https://tsavolion.github.io/capstone_images/countybycounty12.png)



Before we compare these two election results any further, we first need to address the changes in the electoral map. The voting districts of Pennsylvania were redrawn and took effect in 2013.



![](https://tsavolion.github.io/capstone_images/cd2012pa.jpg)



As a result, PA lost a congressman, congressional vote, and ended in a highly skewed district map. In the current map, they only have 18 districts.


![](https://tsavolion.github.io/capstone_images/PACD2016.png)


Observe the how districts 11, 15, and 17 were changed. Where they were once three balanced districts, the Republican architects of this redraw pushed all Democrat voters into District 17 suring up wins in 11 and 15 going forward.

This is how Pennsylvania looks Congressionally now.


![](https://tsavolion.github.io/capstone_images/PACDbyparty.png)



With 13 Republican and 5 Democrat congressmen, Pennsylvania looks far from a battleground state - it looks completely GOP-dominated. Why, then, did almost every pollster determine Pennsylvania was a battleground state or even that it was dependably voting for Hillary Clinton? Take a look at the data.

Trump won 56 counties in Pennsylvania, while Hillary Clinton only won 11. It took 1,911,292 voters in those 11 counties to hand Hillary the win there. However, it took a mere 1,757,406 voters across 56 counties to give Trump an overwhelming victory in those counties. That's right, Trump won five times as many counties as Hillary with less voters than it took Hillary to win 11 counties. Pennsylvania however is a winner-take-all state, so the fact that Trump eclipsed Clinton in rural counties yet stayed competitive with her in semi-urban counties was the eventual key to his victory.

Trump Counties:


![](https://tsavolion.github.io/capstone_images/TWins.png)

Clinton Counties:


![](https://tsavolion.github.io/capstone_images/CWins.png)

![](https://tsavolion.github.io/capstone_images/2016electionresults.png)

To put that in context, please view the total state results here:


![](https://tsavolion.github.io/capstone_images/totalvotes.png)



With the Presidential election results put aside, the fact of the matter is that Pennsylvania is nearly 50% Democrat but that is not represented in congressional districts. The fact that Pennsylvania has been so severely Gerrymandered that it is disenfranchising voters is wrong.

The idea of Congressional districts needing to be continuous landmasses is outdated. I believe that voting districts should be representative of the state's population. While still keeping the political legitimacy of counties in tact, I have created a program to redraw voting districts in order to maximize their effectiveness in representing the people.

I found that clustering Pennsylvania into three separate groups is the best way to represent the population.


![](https://tsavolion.github.io/capstone_images/3districts.png)



Using demographic and economic data, as I segmented Pennsylvania into 3 districts, I found that the areas were most representative of urban, semi-urban, and rural populations. The populations of these three areas are culturally similar and so are their political leanings. Subdividing these three "Super Districts" into six sub-districts each would yield congressional representation that actually represents the population best.


Sources: Census.gov, PA Department of State, ElectionReturns.pa.gov, PA Voter Services
