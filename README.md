# 🏏 IPL Win Predictor
[![Python](https://img.shields.io/badge/Made%20With-Python%203.9-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-red?style=for-the-badge&logo=streamlit)](https://www.streamlit.io/)

Welcome to the IPL Win Predictor! This project uses a **Logistic Regression** model to forecast the win probability of a chasing team in a live IPL match. Turn raw data into game-changing insights!

## About This Project

The IPL Win Predictor is a machine learning tool designed to calculate the real-time probability of an IPL match outcome. By analyzing crucial in-game metrics like the required run rate, balls remaining, and wickets in hand, the model provides a percentage chance of victory for the batting team.

## Project Preview



## Explore the Project

Experience the predictor in action by visiting the live application.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Predictor-brightgreen)](https://ipl-match-predictor.streamlit.app/)

### Features

* **Live Win Probability:** Get instant predictions on which team is more likely to win.
* **Interactive Controls:** A clean and simple UI built with Streamlit allows you to input match scenarios easily.
* **Data-Driven Insights:** Understand how the game state influences the outcome based on historical match data.
* **Fully Deployed:** Hosted on Streamlit Cloud for public access without any local setup.

## How to Use

To get a prediction, you need to input the current state of the second innings:

* **Batting Team:** The team that is currently chasing the target.
* **Bowling Team:** The team that is defending the target.
* **Venue/City:** The city where the match is being played.
* **Target:** The total runs the batting team needs to score to win.
* **Score:** The current score of the batting team.
* **Overs Completed:** The number of overs the batting team has faced.
* **Wickets Out:** The number of wickets the batting team has lost.

The model will process these inputs and display the win probability for both teams.

## Tech Stack

This project is built using the following open-source technologies:

* **Python:** The core programming language for model development.
* **pandas & NumPy:** For efficient data manipulation and numerical operations.
* **Scikit-learn:** For building and training the Logistic Regression model.
* **Streamlit:** To create and deploy the interactive web application.

## Installation

To run this project locally, follow these steps:

1.  Clone the repository to your local machine using this command:
    ```shell
    git clone [https://github.com/rajatrawal/ipl-win-predictor.git](https://github.com/rajatrawal/ipl-win-predictor.git)
    ```
2.  Navigate to the project directory:
    ```shell
    cd ipl-win-predictor
    ```
3.  Install the required Python libraries:
    ```shell
    pip install -r requirements.txt
    ```
4.  Run the Streamlit app locally:
    ```shell
    streamlit run app.py
    ```
5.  Open the provided local URL in your web browser to access the IPL Win Predictor.

## Make Your Prediction

Ready to test your cricket knowledge? Head over to the [**Live Demo**](https://ipl-match-predictor.streamlit.app/) and see how different match situations affect the outcome. Enhance your viewing experience with data-backed predictions!

## Contribute

Contributions are welcome! If you have ideas for new features or find a bug, please open an issue or submit a pull request on the project's [**GitHub Repository**](https://github.com/rajatrawal/ipl-win-predictor).

Thank you for checking out the IPL Win Predictor. Enjoy the game! 🏏✨
