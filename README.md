# Beyond-Goals-Advancing-Soccer-Analytics-with-the-VAEP-Framework

# Introduction

Soccer is a game of intricate strategies and dynamic play, where the impact of individual actions on the game outcome often goes beyond what traditional metrics capture. Inspired by the work of Decroos et al. (Decroos2019ActionsSpeak), this project aims to utilize StatsBomb data to apply and extend the VAEP methodology, offering deep insights into player contributions beyond goals and assists.

# Methodology

This section outlines the data preprocessing steps to fit the SPADL format, the application of the VAEP framework for action valuation, and the analysis techniques used to derive insights from the processed data.

## Data Processing

We transformed StatsBomb data into the SPADL format, ensuring a standardized representation of player actions, facilitating subsequent analyses.

## Action Valuation and VAEP Framework

The VAEP framework evaluates each player action by estimating its impact on changing the probability of scoring and conceding goals. By calculating the difference in these probabilities before and after an action, VAEP assigns a numeric value to each action, reflecting its contribution towards a team's performance. This mechanism allows us to systematically assess the effectiveness of player actions in a way that traditional statistics cannot capture.

# Results

Our comprehensive analysis using the VAEP framework on StatsBomb data revealed significant insights into individual player performances across the Premier League, as shown in the table below.

| **Player**            | **Team**              | **VAEP per 90** |
|-----------------------|-----------------------|-----------------|
| Rodrigues da Silva    | Chelsea               | 1.294           |
| Agüero                | Manchester City       | 1.242           |
| Jamie Vardy           | Leicester City        | 1.145           |
| Harry Kane            | Tottenham Hotspur     | 1.119           |
| Romelu Lukaku         | Everton               | 0.902           |
| Daniel Sturridge      | Liverpool             | 0.825           |
| Diego Costa           | Chelsea               | 0.754           |
| Riyad Mahrez          | Leicester City        | 0.746           |
| Jermain Defoe         | Sunderland            | 0.744           |
| Odion Jude Ighalo     | Watford               | 0.733           |
| Alexis Sánchez        | Arsenal               | 0.711           |
| Olivier Giroud        | Arsenal               | 0.688           |
| Andy Carroll          | West Ham United       | 0.681           |
| Aleksandar Mitrović   | Newcastle United      | 0.679           |
| Graziano Pellè        | Southampton           | 0.658           |
| Shane Long            | Southampton           | 0.655           |
| Christian Benteke     | Liverpool             | 0.636           |
| Tyler Roberts         | West Bromwich Albion  | 0.632           |
| Troy Deeney           | Watford               | 0.631           |
| Callum Wilson         | AFC Bournemouth       | 0.574           |

The results showcase the diversity of impact across teams and highlight players who may not always be in the spotlight yet contribute significantly to their teams' potential for scoring.

## Correlation Analysis

Our findings exhibit a robust correlation coefficient of 0.923 between players' VAEP values and their teams' goal differentials, emphasizing the VAEP framework's capability to predict team performance based on individual contributions. The analysis between halves shows a correlation of 0.662, suggesting varying influences across the match that could affect player performance metrics.

# Conclusion

Through the application of the VAEP framework to StatsBomb data, this project has illuminated the nuanced contributions of players beyond traditional metrics. Our analysis not only identifies the premier talents but also highlights unsung heroes, offering clubs a comprehensive tool for strategic planning and player development. By leveraging advanced analytics, we unlock new dimensions of soccer intelligence, fostering a deeper appreciation for the sport's complexity and strategic depth.

