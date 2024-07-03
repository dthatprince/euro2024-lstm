# Euro 2024 Elections: LSTM Text Prediction Model

## Project Description:
This project utilizes an LSTM (Long Short-Term Memory) model to perform text completion and prediction. The training data is sourced from the Wikipedia page about the 2024 European Parliament elections. The model is designed to predict the next word in a given sequence of text, demonstrating the capabilities of LSTM networks in handling sequential data.

## Data Source
- https://en.wikipedia.org/wiki/2024_European_Parliament_election

## Model Architecture
- Embedding Layer: Converts the input text into dense vectors of fixed size.

- LSTM Layer: Processes the sequential data and captures dependencies between words.

- Dense Layer: Outputs the probability distribution over the vocabulary for the next word prediction.

## Results
After training the model for 100 epochs, the model can predict the next word in a given text sequence with a reasonable level of accuracy.

Screenshot:
