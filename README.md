# March-Mania-Bracket-Prediction

This notebook takes game data from the last 20 years of Season game and March Mania tournament game results, then creates a CSV file with the win probability between every possible match up between teams. Add the current year's games(and modify the path for the training data); this data will be used to engineer features used for training the model. XGBoost trains on the previous and current season data, then will generate predicitions for that year's March Mania competition.
![brack](https://user-images.githubusercontent.com/33522459/171500944-7fe1c5a3-8354-4049-979c-c6640e337afe.jpg)
