

Natural Language Processing with Disaster Tweets

Этот проект — решение задачи классификации твитов, размещённой на Kaggle в рамках соревнования Natural Language Processing with Disaster Tweets.

Описание задачи

Цель — построить модель, которая классифицирует, относится ли твит к реальному бедствию (1) или нет (0).
	•	Тип задачи: бинарная классификация
	•	Метрика качества: F1-score
	•	Данные: текстовые сообщения (твиты), метки классов и дополнительные признаки (keyword, location)



Используемые технологии
	•	Python 3.x
	•	pandas, NumPy — работа с данными
	•	scikit-learn — базовые модели (Logistic Regression, Naive Bayes)
	•	NLTK / spaCy — очистка текста
	•	TensorFlow / PyTorch — модели на основе нейросетей
	•	Hugging Face Transformers — предобученные модели (например, BERT, DistilBERT)

Подход к решению
	•	Очистка текста: удаление URL, знаков препинания, стоп-слов, токенизация
	•	Базовые модели: TF-IDF + Logistic Regression
	•	Нейросетевые подходы: fine-tuning предобученных трансформеров (BERT, RoBERTa)
	•	Построение пайплайнов, кросс-валидация, подбор гиперпараметров
	•	Финальная модель — ансамбль нескольких подходов


Как использовать
	1.	Клонировать репозиторий:

git clone https://github.com/yourusername/nlp-disaster-tweets.git
cd nlp-disaster-tweets


	2.	Установить зависимости:

pip install -r requirements.txt


	3.	Запустить ноутбук:

jupyter notebook notebooks/your_model.ipynb



Ссылки
	•	Страница соревнования на Kaggle
	•	Документация по Transformers

Обратная связь

Если у вас есть предложения, замечания или улучшения — создайте issue или сделайте pull request.

