# Autocorrect with Python

This is a simple autocorrect system implemented in Python using the Jaccard similarity metric. The system reads a text file, processes the text to extract unique words and their frequencies, calculates word probabilities, and provides autocorrection suggestions for input words.

## Installation

To use this autocorrect system, follow these steps:

1. Clone the repository to your local machine using the following command:
```bash
   git clone https://github.com/your-username/autocorrect-python.git
```
2. Navigate to the repository directory:
```bash
  cd autocorrect-python
```
3. Install the required Python packages using pip:
```bash
  pip install textdistance pandas numpy
```
## Usage

- Place the text file you want to use for training in the same directory as the script. Ensure the text file is named moby.txt.

- Run the Python script using your preferred method (e.g., Jupyter Notebook or command line):
```bash
python autocorrect.py
```
The script will read the text file, process the data, and provide autocorrection suggestions for input words.

## How It Works
- The autocorrect system works as follows:
  - Reads the moby.txt file and processes the text data.
  - Calculates the frequency of each word and their probabilities.
  - Implements an autocorrect function that uses the Jaccard similarity metric to suggest corrections for misspelled words.
  - Displays the suggestions based on similarity and probability.

## Contributions
Contributions to this autocorrect system are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
