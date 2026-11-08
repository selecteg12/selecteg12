<div align="center">

<p><a href="https://github.com/selecteg12/selecteg12/blob/main/README.md">English</a> | <strong>Русский</strong></p>

<h1>Привет, я Егор</h1>

<p>Студент 4-го курса направления «Прикладная математика и информатика» · Москва</p>
<p><strong>Ищу стажировку в аналитике данных</strong></p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="SQL и PostgreSQL" />
  <img src="https://img.shields.io/badge/Machine_Learning-F7931E?style=flat-square&amp;logo=scikitlearn&amp;logoColor=white" alt="Машинное обучение" />
  <img src="https://img.shields.io/badge/AI_Applications-7C3AED?style=flat-square" alt="ИИ-приложения" />
</p>

</div>

[Аналитика данных](#аналитика-данных) · [Машинное обучение](#машинное-обучение) · [ИИ и автоматизация](#ии-и-автоматизация) · [Приложения](#приложения) · [PM](#pm)

## Аналитика данных

| Проект | Вопрос | Работа и результат |
| --- | --- | --- |
| [A/B-тест BitMotion](https://github.com/selecteg12/bitmotion-ab-test) | Повышает ли новый интерфейс магазина конверсию в покупку в течение семи дней? | Анализ на уровне пользователей: **9 963 участника**, проверки эксперимента, оценка прироста и доверительных интервалов. Наблюдаемый прирост — **1,73 процентного пункта**. Двусторонний 95%-й доверительный интервал включает ноль. Есть воспроизводимый скрипт и сохранённые результаты. |
| [Анализ продаж билетов](https://github.com/selecteg12/event-ticket-sales-analysis) | Как различаются продажи по сезонам, регионам и типам устройств? | Проанализировал данные в PostgreSQL и Python. Около **53% заказов** в обработанной выборке пришлось на три региона. [Дашборд DataLens](https://datalens.yandex/l4t1anvif4bm5?tab=mg) |
| [Анализ рынка недвижимости](https://github.com/selecteg12/real-estate-analysis) | Как меняются характеристики квартир, срок размещения объявлений и сезонная активность? | Запросы PostgreSQL с CTE, оконными функциями и перцентилями, а также [дашборд DataLens](https://datalens.yandex/ngd6s7nfao0u7). Снятие объявления с публикации не считается подтверждением продажи. |

## Машинное обучение

| Проект | Задача и подход | Результаты и особенности |
| --- | --- | --- |
| [Mogzilla](https://github.com/selecteg12/mogzilla) | Экспериментальный анализ портретов с 478 ключевыми точками, проверкой качества фото и разбором измерений. | Python/FastAPI, React и TypeScript. [Открыть приложение](https://mogzilla.2-27-32-143.sslip.io/) |
| [cat/dog CNN](https://github.com/selecteg12/cat-dog-CNN) | Классификация изображений кошек и собак собственной свёрточной нейросетью, обученной с нуля в TensorFlow/Keras. Проверены 25 000 изображений, удалены точные дубликаты; обучающая, валидационная и тестовая выборки не пересекаются. | **Точность на тестовой выборке — 90,18%** (3 380 / 3 748 изображений). Есть блокнот Colab, кривые обучения, метрики по классам, скриншоты, демо с фотографиями и пакетное получение предсказаний с выгрузкой в CSV. Без предобученных весов. |

## ИИ и автоматизация

| Проект | Что делает | Технические особенности |
| --- | --- | --- |
| [Planner AI Assistant](https://github.com/selecteg12/planner-ai-assistant) | Интерфейс в Telegram для просмотра и изменения задач, событий, привычек, идей и напоминаний в планировщике. | Вызов инструментов через LLM, проверка операций, привязка аккаунта, подтверждение удаления, сохранение состояния, напоминания по расписанию и автоматизированные тесты. |

Ассистент и [веб-приложение Planner](https://github.com/selecteg12/planner-app) используют общие данные в Supabase.

## Приложения

| Проект | Продукт | Реализация и материалы |
| --- | --- | --- |
| [Planner](https://github.com/selecteg12/planner-app) | Веб-приложение для личного планирования: задачи, календарь, привычки и статистика продуктивности. | Next.js, React, Supabase и PostgreSQL. Отдельная ИИ-интеграция с Telegram доступна в репозитории ассистента. |
| [English Buddy](https://github.com/selecteg12/english-buddy) | Помощник для Windows: показывает значения выделенных английских слов и сохраняет их для изучения. Англо-русский словарь входит в комплект. | Electron, React, TypeScript и модуль на C# для Windows UI Automation. [Версия для Windows](https://github.com/selecteg12/english-buddy/releases/tag/v0.1.3), [список изменений](https://github.com/selecteg12/english-buddy/blob/codex/initial-release/CHANGELOG.md) и [отчёт о проверках](https://github.com/selecteg12/english-buddy/blob/codex/initial-release/VERIFICATION.md). |

## PM

| Проект | Описание |
| --- | --- |
| [Alfa AutoML Hackathon](https://github.com/selecteg12/alfa-automl-hackathon) | AutoML-агент для табличных данных. Сравнивает модели и сохраняет предсказания. |

## Инструменты и методы

| Направление | Технологии и методы |
| --- | --- |
| Анализ данных | Python, SQL, PostgreSQL, pandas, NumPy, Matplotlib, Seaborn, DataLens |
| Статистика | A/B-тестирование, анализ конверсии, доверительные интервалы, проверка гипотез |
| Машинное обучение | scikit-learn, LightGBM, CatBoost, XGBoost, TensorFlow/Keras |
| Компьютерное зрение | TensorFlow/Keras, свёрточные нейросети, PyTorch, OpenCV, MediaPipe, ключевые точки лица, FastAPI |
| ИИ-приложения | API языковых моделей, вызов инструментов, Node.js, Telegraf, Supabase |
| Разработка приложений | JavaScript, TypeScript, React, Next.js, Tailwind CSS, Electron |
| Разработка и проверка | Git, GitHub, автоматизированные тесты |

<details>
<summary>Учебные материалы</summary>

- [AI for Beginners](https://github.com/selecteg12/AI-For-Beginners) — личный форк учебного курса Microsoft.
- [ML for Beginners](https://github.com/selecteg12/ML-For-Beginners) — личный форк учебного курса Microsoft.

Это учебные материалы с указанием авторов оригинала.

</details>
