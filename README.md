
# TOPSIS Model Evaluation for Text Summarization

## Overview
This repository contains the implementation of the TOPSIS method to evaluate various pre-trained models for the task of text summarization, using the Gigaword dataset. The models are evaluated based on performance metrics like ROUGE and BLEU scores, as well as efficiency metrics such as inference time, model size, and memory usage.

## Repository Contents
- `evaluation_script.py`: The main script for generating summaries, evaluating them, and applying the TOPSIS method.
- `images/`: Directory containing plots of model evaluations.
  - `topsis_score_ranking.png`
  - `rouge_bleu_comparison.png`
  - `efficiency_metrics_comparison.png`
- `data/`
  - `gigaword/`: Placeholder for Gigaword dataset used for model evaluation. Dataset not included due to size and licensing.

## Setup and Requirements
To run the evaluation script, you will need Python 3.6 or later, with the following packages installed:
- `transformers`
- `datasets`
- `nltk`
- `matplotlib`
- `pandas`
- `numpy`

You can install the necessary packages with:
```
pip install transformers datasets nltk matplotlib pandas numpy
```

## Usage
To execute the evaluation script, run:
```
python evaluation_script.py
```
This will generate the summaries, calculate the performance metrics, apply the TOPSIS method, and save the plots in the `images/` directory.

## Results
The models are ranked using the TOPSIS score based on their performance and efficiency. The plots in the `images/` directory provide a visual comparison of the scores and metrics.

## License
The code in this repository is released under the MIT license. See the `LICENSE` file for more details.

## Acknowledgements
This evaluation was conducted as part of an academic assignment on the application of multi-criteria decision-making methods in machine learning model evaluation.
