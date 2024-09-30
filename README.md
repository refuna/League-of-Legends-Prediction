# League of Legends Match Prediction

## Overview
League of Legends (LoL) is a multiplayer online competitive game developed by Riot Games. In the game, players control heroes, each with a unique set of abilities. The objective is for teams of five players to battle against each other in order to destroy the opposing team's base crystal. The crystals are protected by defense towers, which must be destroyed before reaching the crystals.

Heroes start weak and must kill minions, wild monsters, and opposing heroes to earn gold and experience. Players use experience to level up heroes and skills, while gold is used to buy equipment to enhance various attributes such as attack and defense. Vision control is also key to success, as areas not near friendly units are hidden from view. Both teams can place wards to gain vision and control key areas of the map, forming part of their strategy and tactics.

## Dataset Description
This dataset, sourced from [Kaggle](https://www.kaggle.com/), contains data from 9,879 ranked matches, specifically from Diamond 1 to Masters ranks. All matches feature high-level players, and the dataset records the first 10 minutes of each match. The dataset contains 38 features, 19 for each team (Red and Blue), with characteristics such as:

- **Hero Kills and Deaths**
- **Gold Earned**
- **Experience Points**
- **Hero Leveling**

Though the matches typically last between 30 to 40 minutes, the first 10 minutes significantly influence the outcome of the game. By analyzing these early game metrics, the dataset can help quantify in-game strategies and player performance, potentially offering insights into improving both individual and team play.

## Features
Each match in the dataset provides detailed statistics on both the Red and Blue teams. Key features include:

- **Kills/Deaths**: The number of kills and deaths per team during the first 10 minutes.
- **Gold**: The amount of gold earned by each team.
- **Experience**: The experience points accumulated, which allow heroes to level up.
- **Hero Leveling**: The level progression of each team's heroes within the first 10 minutes.
- **Vision Control**: Wards and map vision during the early stages of the game.

These features provide a comprehensive view of early-game performance and how it correlates with overall match outcomes.

## Importance of Early Game
In League of Legends, the early game can be a critical indicator of the match's trajectory. Players and teams that gain a significant advantage in the first 10 minutes often dictate the pace of the game. This dataset enables a deep dive into early-game dynamics, providing key insights into:

- How early gold, experience, and kills influence later stages.
- The correlation between early leads and match victory.
- Differences in early-game performance between high-level ranked players (Diamond 1 to Masters).

## Application
- **Game Strategy Analysis**: By studying early-game data, teams and coaches can refine their strategies to optimize gold and experience acquisition.
- **Player Performance Evaluation**: Helps assess individual player contributions and their efficiency in the early stages of the game.
- **eSports Development**: Provides valuable insights for game developers and analysts to improve gameplay balance and competitive fairness in high-level matches.

## Conclusion
As one of the most successful eSports titles, League of Legends offers vast potential for data analysis. By studying high-level ranked matches, this dataset helps to quantify key early-game metrics and their impact on match outcomes. This research can lead to a better understanding of the game and inspire future development and improvement within the competitive landscape.

## Dataset Source
The dataset is available on [Kaggle](https://www.kaggle.com/), and it contains detailed information from 9,879 ranked matches between Diamond 1 and Masters players.

