# Positive Negative Detector

Positive Negative Detector is a Python tool that predicts whether a given sentence is positive or negative using sentiment analysis. It is based on the Sentiment140 dataset, a widely used dataset for sentiment analysis containing tweets labeled as positive or negative.

Sentiment analysis is the process of determining the sentiment or emotion expressed in a piece of text. Positive Negative Detector utilizes machine learning techniques to analyze the sentiment of text data and classify it as either positive or negative.


## Usage

1. Clone the repository:

   ```
   git clone https://github.com/deusbalatro/positive-negative-detector.git
   ```

2. Navigate to the project directory:

   ```
   cd positive-negative-detector
   ```

3. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

   **Note:** If you encounter an error related to missing Microsoft Visual C++ Build Tools during the installation of dependencies, make sure to install the tools from [Microsoft's official website](https://visualstudio.microsoft.com/visual-cpp-build-tools/).

4. Run the `main.py` script:

   ```
   python main.py
   ```

   Follow the instructions and enter a sentence when prompted. The tool will then classify the sentiment of the sentence as either positive or negative.

## Dependencies

- joblib==1.3.2
- nltk==3.8.1
- scikit-learn==0.24.2


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
