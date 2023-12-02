---

# Sentiment Analysis on Song Lyrics

## Overview

This repository contains a Python script for performing sentiment analysis on song lyrics. The analysis is based on the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool from the Natural Language Toolkit (NLTK). The script allows users to analyze the sentiment of lyrics for a single artist or compare the sentiment between two artists.

## Dependencies

- Python 3
- pandas
- nltk
- matplotlib
- numpy
- tqdm

You can install the required dependencies using the following command:

```bash
pip install pandas nltk matplotlib numpy tqdm
```

## How to Use

### 1. Analyze the Sentiment of a Single Artist

Run the script and choose option 1 when prompted. Then, select the artist you want to analyze from the provided list. The script will generate a detailed sentiment analysis report, including the distribution of sentiment in the artist's lyrics and a bar graph of compound sentiment scores.

### 2. Compare the Sentiment of Two Artists

Run the script and choose option 2 when prompted. Select the first and second artists you want to compare from the provided list. The script will generate individual sentiment analysis reports for each artist and a bar graph for visual comparison.

## Datasets

The script comes with pre-loaded datasets for several artists, including Ariana Grande, Beyonce, Billie Eilish, Ed Sheeran, Justin Bieber, Katy Perry, Charlie Puth, Maroon 5, Post Malone, Rihanna, Selena Gomez, Coldplay, Drake, and Dua Lipa. Users can easily add their own datasets by following the provided format.

## Results

The script outputs the following results:

- Percentage of positive, negative, and neutral comments for each artist.
- Distribution of sentiment in lyrics through a pie chart.
- Individual sentiment analysis bar graph for each artist.
- Visual comparison of sentiment analysis results between two artists.

## Contributions

Feel free to contribute to this project by adding new features, improving existing functionality, or providing feedback. Create a pull request or open an issue to get started.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
