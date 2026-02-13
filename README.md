<h1 align="center">Привет, я Андрей Кузнецов 👋</h1>
<h3 align="center">Python Backend Developer / ML Engineer (Medical AI)</h3>

<p align="center">
  <a href="mailto:20kas04@gmail.com"><img src="https://img.shields.io/badge/Email-20kas04%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>
  <img src="https://img.shields.io/badge/Location-Ivanovo-0A66C2?style=for-the-badge" alt="location"/>
  <img src="https://img.shields.io/badge/Age-21-2E8B57?style=for-the-badge" alt="age"/>
</p>

## 👨‍⚕️ Обо мне
Студент 5 курса ИвГМУ (лечебное дело), развиваюсь на стыке медицины и AI.

Разрабатываю ML-системы для клинических задач:
- стратификация пациентов;
- прогнозирование клинических исходов;
- интерпретируемые модели для поддержки врачебных решений.

Параллельно проектирую backend-сервисы (FastAPI, async SQLAlchemy, PostgreSQL, Redis) для внедрения моделей в реальные workflow.

## 🔬 Ключевые проекты
### 1) Стратификация пациентов с острым коронарным синдромом
ML-система для приоритизации клинической помощи и маршрутизации в ОИТ.

- Данные: клинические признаки, ЭКГ, биомаркеры
- Подход: `Isolation Forest` + `KMeans` + `VAE (PyTorch)` + `Optuna`
- Валидация: `Gap Statistic`, `Silhouette`, `Bootstrap (500)`
- Результат: устойчивые клинически значимые кластеры (`Silhouette 0.45+`)

### 2) Прогноз восстановления после инфаркта миокарда
Мультиклассовая модель (летальный исход / частичное / полное восстановление).

- Балансировка: `SMOTE (k_neighbors=2)`
- Модели: `RandomForest (GridSearch)` и `XGBoost`
- Интерпретация: `SHAP TreeExplainer`
- Результат: `F1-Score 0.85+`, ключевые факторы: ФВ, Killip

### 3) Booking API (pet-проект)
Асинхронный REST API с аутентификацией и ролевой моделью доступа.

- Архитектура: `Repository Pattern`, `Dependency Injection`
- Безопасность: `JWT (httpOnly cookies)`, `bcrypt`, `RBAC`
- БД: `PostgreSQL` + `SQLAlchemy async` + `Alembic`

## 🛠 Технологический стек
### ML / Data Science
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6F00?style=flat)
![Optuna](https://img.shields.io/badge/Optuna-3A7AFE?style=flat)
![SHAP](https://img.shields.io/badge/SHAP-5A4FCF?style=flat)

### Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

## 📊 GitHub статистика
<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=android4002&show_icons=true&theme=default&hide_border=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=android4002&layout=compact&hide_border=true" />
</p>

## 🎯 Профессиональные интересы
- Машинное обучение в медицине
- Биомедицинский анализ данных
- Clinical Decision Support Systems (CDSS)
- Backend разработка для ML-продуктов

---
📌 Открыт к сотрудничеству в проектах на стыке **AI + медицина + backend**.
