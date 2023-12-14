# Enhanced 2048 AI Solver with Optimized Heuristics
![alt text](imgs/playing_2048.gif)


## Overview
This project builds upon an existing AI solver for the popular puzzle game 2048, originally developed using the minimax algorithm and Selenium WebDriver. My contribution involves creating and testing new heuristics, aiming to maximize the AI's scoring potential in the game. This work is part of my final project for CSCI 4511W, where I explored various strategies to enhance the AI's decision-making process.

## Background
The base AI was capable of playing 2048 by making decisions using the minimax algorithm. My focus was on experimenting with different heuristics to see how they affect the AI's performance. The goal was to find the optimal balance of strategies that would consistently yield higher scores and potentially reach the 2048 tile more frequently.

## New Heuristics Implemented
- **Average Tile Value**: Calculates the average value of non-empty tiles.
- **Border Tile Maximization**: Focuses on maximizing the value of tiles on the game board's borders.
- **Empty Tile Prioritization**: Prioritizes moves that result in the highest number of empty tiles, promoting game longevity.
- **Corner Tile Maximization**: Aims to keep the highest valued tiles in the corners of the board.
- **Combined Heuristic Approach**: A weighted combination of the above heuristics to balance different strategic elements.

## Methodology
Each new heuristic was rigorously tested against various depth cutoffs within the minimax algorithm. The effectiveness of these heuristics was measured by comparing the AI's average scores across multiple game runs.

## Results and Observations
The experimentation led to interesting findings on how different strategies impact the AI's performance. A detailed discussion of these results can be found in the project report.

## Running the Project
- **Main File**: `game_loop.py`
- When executed, this script opens Chrome and starts the AI playing 2048.
- The AI uses the optimized heuristics for decision-making.

## Further Development
This project opens avenues for further exploration in AI game-solving strategies. Future work can involve deeper analysis of heuristic combinations or the integration of machine learning techniques.

## Acknowledgements
Original AI and codebase by Dorian Lazar (https://github.com/lazuxd/playing-2048-with-minimax).


Happy exploring and enhancing the AI for 2048!
