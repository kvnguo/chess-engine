# Chess Engine with Machine Learning

Welcome to the Chess Engine with Machine Learning project! This project aims to develop a chess engine capable of making intelligent moves using machine learning techniques.

## Overview

This chess engine is built using Python and incorporates various libraries and tools for implementing the game logic and integrating machine learning for move evaluation. The project leverages the python-chess library for chess logic and move generation and utilizes machine learning algorithms for improving move selection and evaluation.

## Features

- **Game Logic**: Implements the rules of chess using the python-chess library, including move generation, legality checking, and game state management.
- **Machine Learning Integration**: Utilizes machine learning models to enhance move selection and evaluation, improving the engine's gameplay over time.
- **Customizable**: Offers options for users to customize the engine's behavior, such as depth of search and evaluation parameters.
- **Documentation**: Detailed documentation explaining the engine's architecture, algorithms used, and how to use and extend the engine.

## Installation

1. Clone the repository: git clone git@github.com:kvnguo/chess-engine.git
2. Install dependencies: pip install -r requirements.txt
3. Download the chess.com games dataset from [Kaggle](https://www.kaggle.com/datasets/dimitrioskourtikakis/gm-games-chesscom) and place it in the `data/` directory.
4. Run the engine: python main.py

## Dependencies

- **python-chess**: Core library for implementing chess logic and move generation.
- **numpy**: Fundamental package for scientific computing with Python, used for array manipulation and data handling.
- **pandas**: Data manipulation library for working with datasets, including the chess.com games dataset.
- **scikit-learn**: Machine learning library for building and training models for move selection and evaluation.
- **tensorflow / PyTorch**: Deep learning frameworks for implementing advanced machine learning models if needed.
- **matplotlib / seaborn**: Data visualization libraries for analyzing engine performance and presenting results.
- **jupyter**: Interactive computing environment for prototyping code and visualizing data.
- **pytest / unittest**: Testing frameworks for ensuring the correctness and reliability of the codebase.
- **python-dotenv**: Library for managing configuration settings and environment variables.

## Usage

To use the chess engine, follow these steps:

1. Initialize a new game.
2. Make moves using standard algebraic notation.
3. The engine will respond with its move.
4. Continue playing until the game ends.

For more advanced usage and customization options, refer to the documentation.

## Acknowledgments

We would like to thank the creators of the following libraries and resources used in this project:
- [python-chess](https://python-chess.readthedocs.io/en/latest/) - A Python chess library for implementing chess rules and move generation.
- [chess.com games dataset](https://www.kaggle.com/datasets/dimitrioskourtikakis/gm-games-chesscom) - A dataset of games played on chess.com, used for training machine learning models.

## Contact

For questions, feedback, or suggestions, please contact: 
- [kevinguo1011@gmail.com](mailto:kevinguo1011@gmail.com)
- [vincentguo0630@icloud.com](mailto:vincentguo0630@icloud.com)




