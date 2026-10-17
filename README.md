Data Analyst.

## Био
Прошел путь от классического EDA в Pandas и визуализации в Tableau до проектирования отказоустойчивых стриминговых пайплайнов на Kafka и ClickHouse, освоив по дороге продвинутую математику A/B-тестов и Uplift-моделирование, чтобы превращать сырые данные в точки роста прибыли и экономии бюджета.

## 🚀 Ключевые проекты

**1. [Uplift-моделирование для оптимизации бюджета](ссылка_на_uplift_marketing)**
Задача — сэкономить бюджет, таргетируя только тех, кто покупает из-за рекламы. Обучил `TwoModels` (`scikit-uplift`), оценил через Qini и AUUC. **Результат: Uplift +12.2%, экономия 70% бюджета.** Стек: Python, scikit-uplift, ClickHouse, Superset.

**2. [Real-time аналитика событий](ссылка_на_realtime_analytics)**
Пайплайн live-метрик: Kafka → ClickHouse (Kafka Engine + MV) → Superset. **Результат: обработка ~100 событий/сек с задержкой < 1 сек.** Стек: Kafka, ClickHouse, Superset.

**3. [ETL-пайплайн с оркестрацией](ссылка_на_weather_pipeline)**
Автоматизировал сбор и трансформацию геоданных по 419 городам через API → S3 (SeaweedFS) → dbt → ClickHouse. Оркестрация в Airflow, привязка регионов через `Shapely`. **Результат: ежедневный автономный пайплайн + Choropleth-карта 83 регионов в Grafana.** Стек: Airflow, dbt, ClickHouse, Grafana.

**4. [Анализ воронки и юнит-экономики](ссылка_на_vk_pet)**
Анализ потерь в SMS/Push. Витрины на ClickHouse, A/B-тест каналов (MDE, Z-test). **Результат: нашел каналы с аномальным cost-per-delivered, вывел на дашборд в Superset.** Стек: ClickHouse, SciPy, Superset.

**5. [ML-пайплайн оттока с алертингом](ссылка_на_smart_delivery)**
Сквозной DAG в Airflow: Feature Engineering → CatBoost → Telegram-алерты. **Результат: ROC-AUC 0.74, A/B-тест значим (p < 0.001).** Стек: CatBoost, Airflow, ClickHouse.

## 🛠 Стек
SQL (PostgreSQL, ClickHouse) • Python (Pandas, NumPy, SciPy, Scikit-learn, CatBoost, scikit-uplift, kafka-python, boto3, Shapely) • DE / Data Lake (Apache Airflow, dbt, Apache Kafka, YTsaurus, SeaweedFS (S3), Docker, Kubernetes) • BI (Apache Superset, Grafana, Tableau, Plotly, Seaborn) • Stats / ML (A/B-тестирование, Causal Inference, Uplift-моделирование)
