Exercises and assignments for HCDE410: Human Data Interaction. Everything here is a work in progress unless otherwise noted :)

# Assignment 2: Exploring Sources of Bias in Data

This project analyzes potential sources of bias in the Wikipedia Talk Corpus, which was used to develop Google Jigsaw's Perspective API.

## Contents

- `hcde410-a2.ipynb` — data cleaning, demographic analysis, visualizations, and discussion
- `wikipedia_datasets/` — annotator demographic data
- `a2_all_annotator_demographics.csv` — cleaned demographic data
- `LICENSE.md` — license information

## Main findings

The cleaned dataset contains 5,781 annotators. Most workers were male, between ages 18 and 45, and reported that English was not their first language. Demographic data was available for 83.49% of workers who labelled the toxicity dataset.

These imbalances may influence how toxicity is labelled and could cause a trained model to misinterpret unfamiliar dialects, slang, or culturally specific language.

## How to run

Open `hcde410-a2.ipynb` and run all cells. The analysis requires Python, `pandas`, and `matplotlib`.

## AI use note

I used ChatGPT to troubleshoot Python code and improve the clarity of some written interpretations. I reviewed and verified the results using my notebook outputs.

## License

See `LICENSE.md`.