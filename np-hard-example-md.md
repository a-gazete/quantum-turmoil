Consider a problem where you’d like to enumerate/examine every possible combination of set of items. Eg: You’re a nutritionist and have ~200 available food items. You’d like to examine every possible combination to construct a meal plan. Or, you are a student, and would like to build yourself a degree program by examining every possible course combinations a university offers. Or, you are a gardener, and would like to examine every possible combination of plant varieties to design a garden.

How would you decide which ones to take, how would you carry on this process? If you have only say 5 items to choose from, this is an easy process. You have 2<sup>5</sup> = 32 different options to examine – you can find the solution with or without the computer using your intuition. But suppose you have 10 instead of five items. Your number of items doubled but the number of possibilities you need to investigate now far more than doubled – it increased exponentially to 2<sup>10</sup> = 1024.

You still can enumerate all the options with 10 plants at your disposal in a feasible amount of time/resources. But, what if you have hundreds of plants to chose from? And you want to examine all choices one by one-- will show them to your clients as enumerated[^*].

Never mind hundreds – just work 50 different items to choose from. Assuming that a potential solution is fully examined at every nanosecond, it would take 13 days for today’s algorithmic techniques to find the best answer there is. And would take 26 days, twice the time when you have 51, just 1 more item in your items-pool. You might consider lining up several computers and splitting these computations between them, but how far can you go with that? Even if you would stretch the limits of $, space, .. feasibility, how can you catch up with the required, exponentially increasing computational power ? 

What about 60 items – how long would it take to make this calculation when you have 60 items to choose from? 36 years and about 6 months.  

For 88 items, you’d quickly move up to the number of nanoseconds since Big Bang.

And, for a 100 items, the guaranteed optimum solution would take 40.17 trillion years, 2.9 million times the age of universe.

Even if you’d keep waking up to a twice-fast computing power every day, there still are problems of which the solution space to examine would grow faster and you can’t attain/tame their full intractability (can’t overcome their inherent computational intractability). This is just the nature of things in todays computer science technologies. 

[^*]: Depending on the problem domain,  today’s algorithmic techniques offer far smarter solutions than a bare brute-force search of examining every single option there is. However, this can’t be generalized to all cases, which is why we phrase it as "enumerating all options" and/thus emphasizing such extremes in our example.
