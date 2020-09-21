# Code-Mixed Machine Translation Project

This repository contains the project outline for the **Code-Mixed Machine Translation Project** undertaken as part of the ANLP (Advanced Natural Language Processing) course at IIIT Hyderabad by Team **The Triad**: Yash Bhaskar, Sankalp Bahad, and Utsav Shekhar.

## Table of Contents

- [Introduction](#introduction)
- [Scope of the Project](#scope-of-the-project)
- [Challenges](#challenges)
- [Dataset Exploration](#dataset-exploration)
- [Evaluation Metrics](#evaluation-metrics)
- [Literature Review](#literature-review-findings)
- [Research Gap](#research-gap)
- [GitHub Repository Links for Reference Implementations](#github-repository-links-for-reference-implementations)
- [Project Implementation Plan](#project-implementation-plan)
- [Conclusion](#conclusion)

## Introduction

### Problem Statement

- **Niche problem:** Code-Mixed Machine Translation
- Code-mixed data is prevalent in the daily lives of multilingual individuals.
- Machine translation is crucial for bridging the linguistic gap in code-mixed data.
- Limited research exists in the field of code-mixed machine translation.

### Scope of the Project

- Address the challenges of code-mixed machine translation, specifically from Hinglish to English.
- Improve upon baseline results using various techniques.
- Aim to achieve better scores on MT Evaluation Metric.

### Challenges

- Informal nature of code-mixing.
- Lack of formal sources for code-mixed languages.
- Variability in transliteration.
- Code-switching patterns.

## Dataset Exploration

### Available Datasets

1. **Hinglish-TOP dataset**
   - Size: 180,000 generated utterances, 10,000 human-annotated utterances, 170,000 synthetically generated utterances
   - Related Publications: CST5: Code-Switched Semantic Parsing using T5
   - Description: Code-switched semantic parsing dataset with human-annotated and synthetically generated utterances.

2. **Dakshina Dataset**
   - Collection of text in 12 South Asian languages.
   - Includes native script Wikipedia text and parallel data in native script and Latin alphabet.

### Feasibility Assessment

- Hinglish-TOP dataset is a valuable resource for code-switched semantic parsing tasks.
- Diverse data examples with human-annotated and synthetic utterances.
- Connection to CST5 technique suggests its relevance and potential impact.

## Evaluation Metrics

- BLEU Score: Measures similarity between model output and reference translations.
- CoMeT Score: Specifically designed for code-mixed language translation.
- chrF++ (character F-score with better tokenization): Suitable for evaluating code-mixed translations at the character level.

## Literature Review (Findings)

### Paper 1: CoMeT: Towards Code-Mixed Translation Using Parallel Monolingual

- Challenges of code-mixing in informal conversations.
- Data preparation using the Hinglish-TOP dataset.
- Model fine-tuning and post-processing.
- Evaluation metrics: BLEU, CoMeT, chrF++.

### Paper 2: CST5: Data Augmentation for Code-Switched Semantic Parsing

- Addressing the challenge of code-switched semantic parsing.
- Data preparation and preprocessing.
- Evaluation metrics: Naturalness, Semantic Equivalence.
- Impact of CST5 on semantic parsing performance.

## Research Gap

- Identification of gaps in current research:
  1. Informal Nature of Code-Mixing.
  2. Lack of Formal Sources.
  3. Variability in Transliteration.
  4. Code-Switching Patterns.

## GitHub Repository Links for Reference Implementations

### Datasets

1. [Code-Mixed Machine Translation Dataset](https://github.com/devanshg27/cm_translation): Contains raw data and preprocessed versions for training and evaluation.

2. [Hinglish-TOP Dataset](https://github.com/google-research-datasets/Hinglish-TOP-Dataset): A valuable resource for code-mixed language research.

### Baseline Implementation

1. [Indic-Trans](https://github.com/libindic/indic-trans): Transliteration library for Hindi to Roman conversion.

2. [Fairseq](https://github.com/facebookresearch/fairseq): Toolkit for sequence-to-sequence tasks, including machine translation.

## Project Implementation Plan

- Overview of the Proposed Approach
- Tentative Timeline
- Expected Challenges and Mitigation Strategies

## Conclusion

- Summary of the Project Outline
- Importance of Addressing the Code-Mixed Machine Translation Problem
- Anticipated Project Outcomes

--- 
**Note:** The information presented here is part of the project outline and may be subject to updates and modifications during the project's progress.

