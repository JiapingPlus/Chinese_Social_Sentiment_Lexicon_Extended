1_Method：

1_1_Word2Vec_expanded_words_list：使用Word2Vec方法所得到的五个维度的扩展词汇词表，其情感极性还需要进一步筛选。

1_2_Center_weight_expansion_results：使用中心权重法对扩展词汇的情感极性进行重新分配，得到各维度积极扩展词汇数据、各维度消极扩展词汇数据。

--- 1_2_1_Positive_terms_by_dimension：各维度积极扩展词汇数据

--- 1_2_2_Negative_terms_by_dimension：各维度消极扩展词汇数据

1_3_Expanded_wordlist_for_validation：有效性检验所需的扩展词表分类数据集。



2_Procedure：

2_1_Word2Vec_expanded_wordlist_by_dimension：对词表进行扩展的代码

2_2_Center_weight_sentiment_polarity_wordlist：使用中心权重法处理扩展词汇情感极性问题的代码

2_3_Validity_test_ml_classification：对扩展词表进行有效性检验的代码

2_4_Correlation_test_pearson：对扩展词表进行相关性检验的代码