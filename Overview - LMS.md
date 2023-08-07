**Last Man Standing in the English Premier League (EPL) - An Optimization Problem with Lives**

The Last Man Standing game is a strategic optimization challenge played within the context of the English Premier League (EPL) matches. The objective is to create a model that makes the most informed choices across a series of football matches, with the provision of 3 lives for each player.

### Overview:

1. **Objective**: To predict the winning team in a given match week of the EPL, aiming to make correct predictions for as many consecutive weeks as possible.

2. **Participants**: Every player (in this case, a computer model) selects one team they believe will win in the upcoming match week.

3. **Lives**: Each player starts with 3 lives. A life is lost when a wrong prediction is made. Once all 3 lives are lost, the player is eliminated.

4. **Constraints**: Once a team is chosen in a week, it cannot be selected again by the same player in subsequent weeks.

5. **Optimization Goal**: The goal is to create a model that makes optimal selections by analyzing various factors like past performance, player statistics, match conditions, etc. The optimization problem here is to maximize the number of consecutive correct predictions, subject to the constraint of not repeating team choices, and to preserve lives as long as possible.

6. **End Condition**: The game continues until a player loses all 3 lives or until the end of the season.

7. **Winner Determination**: The winner is the player (or model) who has made the most consecutive correct predictions or the last remaining player if all others have lost their lives.

### Model Challenge:

The objective of the model in the Last Man Standing competition is to optimally select a winning team each week from the English Premier League, without selecting the same team more than once in a 20-week cycle. 

The model needs to predict match outcomes effectively by utilising and learning from historical and real-time match data, team statistics, and other relevant information. It should navigate through the changing constraints and dynamics of the competition, and strategise its choices considering both short-term rewards (winning the current week) and long-term strategy (preserving strong teams for later weeks).

To win, the model should make the most accurate predictions possible, while also carefully managing the rule that each team can only be selected once in a cycle. Therefore, the model needs to be adaptive and capable of making informed decisions based on evolving data and constraints. This will optimise the model's ability to maintain its "lives" and ultimately become the Last Man Standing.
