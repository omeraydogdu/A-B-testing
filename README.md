# A-B-testing

# Dataset story

-This notebook uses data from "Mobile Games A/B Testing - Cookie Cats" dataset. It includes A/B test results of Cookie Cats mobile game to examine what happens when the first gate in the game was moved from level 30 to level 40, so when a player installed the game, he or she was randomly assigned to either gate_30 or gate_40. The data we have is from 90189 players that installed the game while the A/B test was running.

-So the dataset already contains two samples, and our work is to prepare the data, formulate a hypothesis, explore the data, and perform statistical tests to check our hypothesis.

# We have five columns in our dataset:

-userid: represents the unique identifiers of the users that installed Cookie Cats game while the A/B test was running;
-version: has two unique values corresponding to two starting levels, it is intended for dividing the data into two samples for performing a statistical test;
-sum_gamerounds: represents the quantity of rounds played by a certain user;
-retention_1: shows how many users returned to the game one day after installing it;
-retention_7: shows how many users returned to the game seven days after installing it.
