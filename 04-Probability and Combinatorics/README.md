# 04 — Probability and Combinatorics

## Overview

This module explores mathematical concepts and practical applications
of probability, combinatorics, signal processing, error-correcting codes,
and probabilistic data structures using Python and Jupyter Notebook.

The exercises combine mathematical explanations, Python implementations,
visualizations, and experimental analysis.

## Topics Covered

### Problem 1 — Exploring Distribution Parameters

- Exploring the binomial and Gaussian distributions.
- Investigating how distribution parameters affect their shapes.
- Visualizing probability distributions using Python.

### Problem 2 — Central Limit Theorem

- Exploring the Central Limit Theorem through simulations.
- Comparing distributions of sample means.
- Analyzing experimental results and convergence toward a normal distribution.

### Problem 3 — Birthday Paradox

- Calculating the probability of shared birthdays.
- Exploring why 23 people are sufficient for a probability above 50%.
- Investigating the birthday attack principle and hash collisions.

### Problem 4 — Having Fun with Functions: Fourier Transform

- Creating and visualizing parametric curves.
- Exploring combinations of sine and cosine functions.
- Understanding the relationship between time and frequency domains.

### Problem 5 — Working with Audio Files: Using the Fourier Transform

- Loading and analyzing WAV audio files.
- Applying the Fast Fourier Transform (FFT).
- Identifying fundamental frequencies and harmonics.
- Visualizing the frequency spectrum of a musical note.

### Problem 6 — Breaking MD5 in Different Ways

- Understanding cryptographic hash functions.
- Demonstrating collisions using truncated MD5 hashes.
- Exploring the birthday paradox in cryptography.
- Investigating rainbow tables, salts, peppers, and password hashing.

### Problem 7 — Audio Filters and Equalizers

- Implementing low-pass and high-pass filters.
- Implementing band-pass and band-stop filters.
- Applying Butterworth filters to audio signals.
- Comparing original and filtered frequency spectra.
- Exploring combinations of filters and audio equalizers.

### Problem 8 — Error-Correcting Codes

- Understanding error detection and correction.
- Implementing Hamming(7,4) encoding and decoding.
- Detecting and correcting single-bit errors.
- Investigating the limitations of Hamming(7,4) with two-bit errors.
- Comparing Hamming codes with SECDED.

### Problem 9 — Probabilistic Data Structures

- Understanding Bloom filters.
- Implementing a Bloom filter using Python.
- Calculating theoretical false-positive probabilities.
- Comparing theoretical predictions with experimental results.
- Investigating the effect of bit-array size.
- Comparing Bloom filter memory usage with Python sets.

## Project Structure

```text
04-Probability and Combinatorics/
├── Probability and Combinatorics Exercise.ipynb
├── c-note.wav
└── README.md
```

## Technologies

- Python 3
- Jupyter Notebook
- NumPy
- SciPy
- Matplotlib
- Python standard library

## Installation

Install the required Python packages:

```bash
pip install notebook numpy scipy matplotlib
```

## Running the Notebook

1. Open a terminal in the module directory.
2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `Probability and Combinatorics Exercise.ipynb`.
4. Run the notebook cells in order.

**Note:** The `c-note.wav` audio file must remain in the same
directory as the notebook for the audio experiments to work.

## Mathematical Models

### Bloom Filter False-Positive Probability

The approximate probability of a false positive is:

$$
p \approx \left(1-e^{-kn/m}\right)^k
$$

where:

- `m` — number of bits in the filter.
- `n` — number of inserted elements.
- `k` — number of hash functions.

The approximately optimal number of hash functions is:

$$
k_{\mathrm{opt}} = \frac{m}{n}\ln 2
$$

### Experimental Results

For a Bloom filter containing 100 inserted elements,
with 1000 bits and 3 hash functions:

- Observed false-positive rate: approximately 2.10%.
- Theoretical false-positive probability: approximately 1.74%.

The results illustrate the relationship between mathematical
predictions and experimental observations.

## Learning Outcomes

After completing this module, the following concepts have been explored:

- Applying probability and combinatorics in Python.
- Analyzing audio signals using Fourier transforms.
- Understanding hash collisions and the birthday paradox.
- Implementing and evaluating digital signal filters.
- Understanding error detection and correction with Hamming codes.
- Implementing probabilistic data structures.
- Comparing theoretical mathematical models with experimental results.

## Conclusion

This module demonstrates how mathematical concepts can be applied
to practical computational problems.

The experiments show that mathematical models provide useful
predictions, while Python simulations help validate these models
and reveal their practical limitations.