# Vietnamese Facebook Social Media Trend Dataset

## Overview

This dataset is a collection of Vietnamese Facebook posts and comments, specifically curated for research in **real-time social media trend analysis**. The content is highly **unstructured**, containing slang, special characters, and noisy text, which poses challenges for traditional natural language processing (NLP) approaches.

Existing keyword-based or clustering techniques often fail to capture the nuances of Vietnamese social media, and even advanced topic modeling methods like **BERTopic** or **LDA** may overgeneralize distinct news stories or fragment identical content across sources. Our dataset and pipeline are designed to address these issues, providing a foundation for more accurate and timely trend detection.

## Dataset Highlights

- **Size:** 2,794 Facebook posts and comments  
- **Language:** Vietnamese  
- **Content Type:** Textual content from Facebook, including posts, comments, slang, memes, and news snippets  
- **Categories:** Seven thematic labels:
  - Movies
  - Music
  - Social News
  - Slang & Memes
  - Travel
  - Entertainment Shows
  - Sports
- **Annotation:** Each post/comment is manually labeled with one of the seven categories, ensuring high-quality supervised data.

## Motivation

Analyzing social media trends in real time is crucial for understanding public sentiment, detecting viral content, and deriving actionable insights. Vietnamese social media presents unique challenges due to:

- Informal language and slang  
- Abundant use of emojis, special characters, and misspellings  
- Rapid spread of content across multiple sources  

Traditional NLP approaches often **overgeneralize** or **fragment topics**, reducing the effectiveness of trend analysis. This dataset is designed to support advanced models that can handle **noisy, informal, and domain-specific Vietnamese text**.
