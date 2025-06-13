# Frequent Itemsets in Bag-of-Words Dataset

This repository contains our solution to the *Frequent Itemsets* problem on the **Bag-of-Words Dataset** (from UCI Machine Learning Repository).

We explored three text collections (Enron emails, NIPS papers, KOS blog entries) and computed frequent K-itemsets of words occurring together in documents.

## Approach

We implemented two versions of the code, evaluated their performance, and selected the faster one to complete the task efficiently. The final code identifies all K-itemsets with frequency ≥ F for given values of K and F.

## Files

- `0_main_code.ipynb` – Our final, optimized code for finding frequent itemsets.
- `0_two_Codes_Comparison.ipynb` – Our two codes and test cases for comparison.
- `enron.ipynb` – Contains runs for the Enron dataset for different (K, F) pairs.
- `KOS_NIPS.ipynb` – Contains runs for the KOS blog entries and NIPS papers datasets for different (K, F) pairs.
- `report.pdf` – Contains:
  - Analysis of how **time taken** and the **number of frequent itemsets** depend on different values of K (itemset size) and F (minimum frequency threshold) across datasets.
  - Time and space complexity discussion of the chosen (final) code.

## Notes

- The assignment was completed as part of the *Data Mining and Machine Learning (DMML)* course offered at CMI.
- **Contributors**: This solution was prepared jointly by [Trishita](https://github.com/Lemon-lbo/) and [Sowmya](https://github.com/Sowmya0667)
- **Dataset**: [UCI Bag of Words](https://archive.ics.uci.edu/ml/datasets/Bag+of+Words)
- This assignment was originally done on February 2025.
