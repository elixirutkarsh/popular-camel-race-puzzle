# popular-camel-race-puzzle
Problem Statement:
You have 25 camels, and you want to find the top three fastest camels among them. However, you can only race five camels at a time on a track that accommodates only five camels. There is no stopwatch or any other means of measuring time. How many races are required to determine the top three fastest camels?

Solution:
To solve this puzzle efficiently, follow these steps:

Divide the 25 camels into five groups of five camels each: A, B, C, D, and E.

Conduct five races, one with each group, on the track. This will determine the fastest camel in each group for each race.

After the first round of races, you have identified the fastest camel from each group. Label them as A1, B1, C1, D1, and E1, where the suffix '1' denotes the fastest camel in each group.

Now, take the five winners from the previous races (A1, B1, C1, D1, and E1) and race them together in a new race. This will determine the overall fastest camel among these five.

After the second race, you will have identified the overall fastest camel. Label it as Winner.

Now, you need to find the second and third fastest camels. From the remaining four camels in the second race (excluding the overall Winner), take the top two finishers and label them as Second and Third, respectively.

Therefore, the Winner is the fastest camel overall, Second is the second fastest camel, and Third is the third fastest camel.
