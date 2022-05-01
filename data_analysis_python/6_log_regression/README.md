* __adult__
<br>Отбор факторов, построение логистической регрессии на данных об уровне дохода
    * визуализации (Matplotlib, seaborn: боксплот, гистограмма)
    * оценка взаимосвязи между категориальным таргетом и числовыми/категориальными факторами (Т-тест, Хи-кв Пирсона)
    * отбор факторов (mutual information)
    * train/test разбивка (sklearn train_test_split)
    * масштабирование и кодирование (sklearn OneHotEncoder, StandardScaler)
    * логистическая регрессия (sklearn LogisticRegression)
    * кросс-валидация (sklearn cross_val_score, RepeatedStratifiedKFold)
    * метрики (accuracy, precision, recall, f1)
* __affair__
<br>Отбор факторов, построение логистической регрессии, построение кривых ROC и PR на данных об внебрачных связях
    * визуализации (Matplotlib, seaborn: боксплот, гистограмма, столбчатая диаграмма)
    * оценка взаимосвязи между категориальными таргетом и факторами (Хи-кв Пирсона)
    * отбор факторов (mutual information)
    * train/test разбивка (sklearn train_test_split)
    * масштабирование и кодирование (sklearn OrdinalEncoder)
    * логистическая регрессия (sklearn train_test_split, LogisticRegression)
    * кросс-валидация (sklearn cross_val_score, RepeatedStratifiedKFold)
    * метрики (accuracy, precision, recall)
    * ROC- и PR-кривые («вручную» и sklearn roc_curve, precision_recall_curve, auc)