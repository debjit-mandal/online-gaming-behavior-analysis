
# Online Gaming Behavior Analysis

This repository contains an in-depth analysis of online gaming behavior using a comprehensive dataset. The dataset includes various metrics and demographics related to player behavior, game-specific details, engagement metrics, and a target variable reflecting player retention.

## Dataset Overview

The dataset captures the following features:

- **PlayerID**: Unique identifier for each player.
- **Age**: Age of the player.
- **Gender**: Gender of the player.
- **Location**: Geographic location of the player.
- **GameGenre**: Genre of the game the player is engaged in.
- **PlayTimeHours**: Average hours spent playing per session.
- **InGamePurchases**: Indicates whether the player makes in-game purchases (0 = No, 1 = Yes).
- **GameDifficulty**: Difficulty level of the game.
- **SessionsPerWeek**: Number of gaming sessions per week.
- **AvgSessionDurationMinutes**: Average duration of each gaming session in minutes.
- **PlayerLevel**: Current level of the player in the game.
- **AchievementsUnlocked**: Number of achievements unlocked by the player.
- **EngagementLevel**: Categorized engagement level reflecting player retention ('High', 'Medium', 'Low').

This dataset can be found in **Kaggle**: [🎮 Predict Online Gaming Behavior Dataset](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset) 

## Objectives

1. Perform exploratory data analysis (EDA) to understand the dataset.
2. Identify key factors influencing player engagement levels.
3. Build predictive models to classify player engagement.
4. Analyze feature importance and provide insights for game design optimization.

## Analysis Steps

### 1. Exploratory Data Analysis (EDA)

- Summary statistics of numerical features.
- Distribution plots for age, play time, session duration, etc.
- Correlation matrix to identify relationships between features.

### 2. Predictive Modeling

- Develop models to predict `EngagementLevel` using features like age, gender, location, game genre, play time, etc.
- Models include decision trees, random forests, logistic regression, and neural networks.

### 3. Additional Analysis

- **Hyperparameter Tuning**: Optimize the performance of the Random Forest model.
- **Model Comparison**: Evaluate different machine learning models including SVM, Gradient Boosting, and Neural Networks.
- **Cross-Validation**: Ensure robustness of the models.

### 4. Summary and Conclusion

- Summarize the findings from the analysis.
- Provide recommendations for future work.

## Files in the Repository

- `online_gaming_behavior_analysis.ipynb`: Jupyter Notebook containing the analysis.
- `online_gaming_behavior_dataset.csv`: Dataset used for the analysis.
- `README.md`: This file.

## How to Run the Notebook

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/debjit-mandal/online-gaming-behavior-analysis.git
    cd online-gaming-behavior-analysis
    ```

2. Ensure you have the necessary dependencies installed. You can create a virtual environment and install the dependencies using:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt 
    ```

3. Open the Jupyter Notebook:

    ```bash
    jupyter notebook online_gaming_behavior_analysis.ipynb
    ```

4. Run the cells in the notebook to perform the analysis.

## Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project is inspired by the growing interest in understanding player behavior in online gaming environments.
- Thanks to the open-source community for providing tools and libraries that make data analysis and machine learning accessible.
