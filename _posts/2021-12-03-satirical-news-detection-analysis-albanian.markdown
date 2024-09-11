---
layout: post
title:  "Satirical News Detection and Analysis in Albanian"
date:   2021-12-03 00:00:00 +0100
categories: machinelearning nlp news albanian data
---
I just published my Satirical News Detection and Analysis in Albanian Interactive Python Notebook on Kaggle! 

This notebook presents a Satirical News Detection and Analysis in Albanian, which uses news articles taken from the Albanian News Article Dataset from two separate sources: (1) Kungulli.com and (2) Kallxo.com, and predicts the type of article using supervised Machine Learning (ML).

![Analysis Results](https://www.kaggleusercontent.com/kf/81027914/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..kv5k-tYkaYmdbJmL8d5dZg.JDVE4NFviYwLjnKKtbzCVZ4RnSJnQX3UQugc1i8EEcMAItVtc0QBDMzpDCxIoV2pKX79BzLXCeU7KtV-2kL3iMMHfmXTQYvjxaOI_P_yhwnsQI1s-kHVRxinuaeLeY4b1PC629e9WTPMNYrQT0jN6zzm62QoRLml0DO3nnsn0Zgms5Gb-hTDnQInB5WawYSBKWpP-tj6W0qnubngkGoAfZW3FBMC4C-GJuFM2enlwt8qjbL-rla7rJzyRfFZZcTr0ivdpUkTZZfpJdz48_SgxHCAafng2uj23S3urzaqmYRAgfRgVdb1frbdW9b_v9otx9xV7F8zJDA656SY6KfYTwCjJXFPonjzAaIwtPFsHsP-nFkDuFNf49Fm5Nj2h04Ggi2xq0_C4I203IHHSgTXxTeEPNeB7spMnTYeHx5qGRGiNTSbCSxPLXL7MRBSTfpU01RuEPV662McBCLb_X5Zy1DvhMA3DQwyVkkL002J_BIBy5DcDC7YIIgvLCo3AC2H5lyjsZDylf5Rs2fQvGa-0MQA6OMhmBTvoy_SuD0lvx13UdVhVUbpfVBdRVPHnkGZINVHqnwGyZhQC2zsyfuoV0EelhfChD3irRWKcbOIe9jEcAb7R3-Zm0VwFdW2hz_gWefl3xchBM3NnTMmO6gYEoW3cYjS1j5hAO6xNLperB3Qb_GyO5ZSqxjjcVdZLJ0T.059SMzVxbNpZ4drN6HwLZA/__results___files/__results___39_1.png)

The experiment was carried out utilizing a Cross-validation (5-fold) setup for internal validation, referred as the training score, and an external testing set for external validation, referred as the testing score. Evaluation includes multiple classifiers, scaling methods, and various article content preprocessing approaches

In summary, this approach combined different classifiers, scaling methods, and text preprocessing approaches to find the best performing pipeline for handling satirical news classification in Albanian, attaining a test set accuracy score of 0.975. To the best of my knowledge, this kind of study has never been published before, and it lays the groundwork for future research in this area, as well as potential expansion to automated fake news detection in Albanian, assuming the necessary data can be obtained.

The notebook can be accessed here: [https://www.kaggle.com/gentrexha/satirical-news-detection-and-analysis-in-albanian](https://www.kaggle.com/gentrexha/satirical-news-detection-and-analysis-in-albanian).
