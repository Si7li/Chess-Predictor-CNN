# Chess-Move-Predictor-CNN
This repository contains a Python project that uses deep learning models to predict the best chess moves given a board position in the FEN (Forsyth-Edwards Notation) format. The project utilizes Convolutional Neural Networks (CNNs) to predict the piece type, destination square's column (alpha), and destination square's row (number) for the next move.

## Overview
- Data preprocessing to convert FEN notation to a format suitable for deep learning.
- Three separate deep learning models for predicting piece type, alpha, and number of the destination square.
- Training and evaluation of these models using a dataset of chess game moves.
- A function to predict the best move for a given FEN board position.
- The model's accuracy could be changed by changing tha dataset or changing the number of epochs.
