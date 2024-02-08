# Sentiment Analysis of Ted Talk by Tierney Thys and David S.Rose
TED Talk Text Analysis: David S. Rose and Tierney Thys
## Introduction
This work delves into the fascinating realm of text analysis by examining the TED talks of two distinct speakers: David S. Rose and Tierney Thys. David S. Rose, a business pitch expert, imparts insights into effective pitching for startups, emphasizing clarity, conciseness, and numerical understanding. On the other hand, Tierney Thys, a Marine Biologist, discusses the enchanting world of giant sunfish and advocates for ocean biodiversity protection. The analysis focuses on their spoken words, aiming to uncover relationships and insights using various analytical methods in R.

## Method
This analysis starts by loading required packages and utilizing the "dsEssex" package. Data preparation is followed by exploration, where the "ted_talks" dataset is tokenized using the tidytext package. Stop words are removed, and word frequencies are calculated. The top 10 words for each speaker are visualized using ggplot2, and captivating word clouds are created. A combined "person" variable merges their names, leading to a visualization of the most spoken words. Sentiment analysis is conducted, and odds ratios are computed to showcase sentiment differences.

## Results
Tokenization and Stopword Removal
The most spoken words for each speaker are displayed. For Tierney Thys, "just" and "little" stand out, while "know" and "want" are prevalent in David S. Rose's talk.

## Bar Chart of Top Words
Bar charts vividly depict the 10 most spoken words for each speaker. "Just" is Tierney's most spoken word, and "Know" is David's most prominent word.

## Combined Speaker Words
A comparison of the first ten words spoken by both speakers is illustrated. Notably, "Know" appears in both speakers' most spoken words.

## Sentiment and Odds Ratio
The sentiment expressed by each speaker is analyzed, revealing differences in sentiment types. Odds ratios and log odds ratios are calculated, highlighting sentiment variations between David and Tierney.

## Word Frequency Comparison
A scatter plot visually compares word frequencies, indicating words more frequently used by one speaker than the other. The dashed line represents equal word usage.

For detailed insights, code, and data, please refer to the complete analysis in the R script on https://rpubs.com/Opeyemi/1075863
