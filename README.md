# Cyrillic URL Project

This repository contains benign url dataset, URL created by cyrillic alphabet and both of these datasets are made public for research and study purpose. 
we have parsed the deep web to gather 50k benign URLs. Then using algorithm, we have created another 50k Cyrillic URLS as describe in the paper. In these URLs, each English character is replaced by look-alike Cyrillic characters. Additionally, We have inserted 5175 benign URLs (containing only English characters) and 5715 malicious English URLs. Thus total dataset contains of 55,715 benign URLs and 55,715 malicious URLs.

- **Dataset 1**: **File**: `cyrillicANDbenign.csv`. This dataset contains nearly 50k samples from each class. 50K benign URLs are collected by web parsing. Label 0 means benign and label 1 means cyrillic URLs.

- **Dataset 2**: **File**: `cyrillic_mixed_dataset (2).csv`. Includes Dataset 1 along with 5,715 malicious URLs and 5,175 benign URLs. The total count is 55,715 benign URLs (in English) and 55,715 malicious URLs (in English). Label 0 indicates benign URLs, and label 1 indicates Cyrillic URLs.
