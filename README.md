# A/B Testing Mobile Games - Cookie Cats

## Overview

Cookie Cats is a popular mobile puzzle game developed by Tactile Entertainment, known for its engaging "connect three"-style gameplay. The game features gates that players encounter as they progress through levels, requiring either waiting or in-app purchases to proceed. These gates not only drive in-app purchases but also aim to enhance player enjoyment and prolong engagement by providing enforced breaks.

In this project, we conduct an A/B test to analyze the impact of moving the first gate in Cookie Cats from level 30 to level 40. Specifically, we investigate the effect of this change on player retention, measured by whether players returned to the game after 1 day (retention_1) and 7 days (retention_7) following installation.

## About the Dataset

### Context

The dataset comprises A/B test results from Cookie Cats, focusing on the shift of the first gate from level 30 to level 40. Players were randomly assigned to either gate_30 (control group) or gate_40 (experimental group).

### Content

The data covers 90,189 players who installed the game during the AB-test period. The key variables include:

- **userid:** A unique identifier for each player.
- **version:** Indicates whether the player belongs to the control group (gate_30) or the experimental group (gate_40).
- **sum_gamerounds:** The number of game rounds played by the player during the first 14 days after installation.
- **retention_1:** Binary indicator of whether the player returned to play 1 day after installing.
- **retention_7:** Binary indicator of whether the player returned to play 7 days after installing.

## Objective

The primary goal is to assess whether the change in gate placement (from level 30 to level 40) has a significant impact on player retention. Through statistical analysis, we aim to provide insights into the potential implications for player engagement and the overall success of the game.

## Analysis Steps

1. **Data Exploration:** Understand the characteristics of the dataset, check for missing values, and explore the distribution of key variables.
2. **A/B Test Analysis:** Conduct statistical tests to compare retention rates between the gate_30 and gate_40 groups.
3. **Visualization:** Create visualizations to illustrate the findings and patterns within the data.
4. **Conclusion:** Summarize the results, draw conclusions about the impact of gate placement on player retention, and offer recommendations for future game development decisions.


