# Project Overview 

Project from DataCamp. 

Cookie Cats, developed by Tactile Entertainment, is a popular mobile puzzle game employing the "connect three" puzzle mechanic, requiring players to link tiles of matching colors to clear the board and advance through levels. An intriguing feature is the inclusion of melodious singing cats, which adds to its uniqueness.

As players advance, they encounter gates that enforce a waiting period before progression or prompt in-app purchases. The objective of this project is to scrutinize the outcomes of an A/B test, wherein the initial gate in Cookie Cats was shifted from level 30 to level 40. The primary focus lies on assessing the repercussions on player retention and game rounds.

## Dataset presentation
The dataset involves 90 189 players who installed the game during the AB-test's execution. Notable variables include:

1. `userid`: A distinct identifier for each player.
2. `version`: Denotes whether the player was assigned to the control group (gate_30, level 30 gate) or the test group (gate_40, level 40 gate).
3. `sum_gamerounds`: Signifies the count of game rounds undertaken by a player within the initial week following installation.
4. `retention_1`: Indicates whether the player revisited and played the game 1 day after installation.
5. `retention_7`: Indicates whether the player revisited and played the game 7 days after installation.

Players were randomly allocated to either the gate_30 or gate_40 group upon installing the game.

## Results and Recommendations 

When assessing day 1 retention, the presence of gates at level 30 or 40 demonstrates minimal impact on the player retention rate. However, as day 7 approaches, the implementation of gates at these levels does indeed affect retention.

Since we know the exact value of the 7 day player retention rate for both groups, we can say that the move to increase gate level from 30 to 40 has a negative impact on this specific metric. The difference is slight but it's significant.

Based on these findings, I recommend maintaining the gate at level 30.
