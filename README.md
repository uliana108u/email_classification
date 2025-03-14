# Email Spam Classifier

## Описание проекта
Данный проект представляет собой систему классификации электронных писем на спам и не спам с использованием трансформер-модели `AutoModelForSequenceClassification` из библиотеки `transformers`. В качестве данных для обучения использовался файл `emailTextsI.csv`, содержащий текст письма и метку (спам/не спам).


## Установка и зависимости
Перед началом работы установите необходимые библиотеки:
```bash
pip install transformers datasets torch scikit-learn pandas
```

## Структура проекта
- **email_classififcation_25.ipynb**: скрипт для обучения модели кдассификации email на Spam или Ham и примера предсказания
- **data/**: папка с датасетами с текстами писем и метками
- **spam_classifier/**: папка для сохраненной обученной модели
- **README.md**


## Почему выбрана AutoModelForSequenceClassification?
`AutoModelForSequenceClassification` была выбрана по следующим причинам:
- **Гибкость**: Позволяет использовать предобученные модели трансформеров, такие как BERT, RoBERTa, DistilBERT и другие.
- **Точность**: Трансформер-модели демонстрируют высокую точность в задачах обработки естественного языка, включая классификацию текста.
- **Легкость использования**: Простая интеграция с `Hugging Face Transformers` позволяет быстро обучать и применять модель.
- **Поддержка GPU**: Ускоренное обучение и инференс благодаря возможности использования графического процессора.

## Контакты
Если у вас есть вопросы, пишите на uliana108u@gmail.com.
