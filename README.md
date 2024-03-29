# NLP_TFIDF
## Classification of long texts using TFIDF and LogReg. / Классификация длинных текстов с применением TFIDF и LogReg.

### Цель: Реализация классического алгоритма классификации текстов с помощью pytorch.

### Результат: Был реализован алгоритм классификаци текстов. Работа была выполнена как часть образовательного курса stepik и it академии samsung. Точность работы алгоритма - 82%

Это работа с классическим датасетом для тематической классификации, "20 новостных групп", который состоит из примерно 20 тысяч сообщений электронной почты, распределенных по 20 категориям. Преобразовываем исходный текст в токены (токенизацию), затем строим словарь, реализуем логистическую регрессию на pytorch, обучим её, оценим её качество. А затем мы возьмём библиотеку scikit-learn (алгоритмы векторизации текстов из неё, а также реализацию логистической регрессии), обучим этот вариант модели и сравним с нашим вариантом.

### Goal: Implementation of a classic text classification algorithm using pytorch.

### Result: A text classification algorithm was implemented. The work was performed as part of the Stepik and It educational course at Samsung Academy. Algorithm accuracy - 82%

This is working with a classic thematic classification dataset, the 20 Newsgroups, which consists of approximately 20 thousand email messages distributed across 20 categories. We convert the source text into tokens (tokenization), then build a dictionary, implement logistic regression in pytorch, train it, and evaluate its quality. And then we will take the scikit-learn library (text vectorization algorithms from it, as well as the implementation of logistic regression), train this version of the model and compare it with our version.
