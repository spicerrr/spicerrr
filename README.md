<div align="center">

# привет! ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif) я лиза

### Junior System Analyst

**B2C / mobile · интеграции · master data · бизнес-процессы**

[![System Analysis](https://img.shields.io/badge/System_Analysis-1f6feb?style=flat-square)](#-коммерческий-опыт)
[![BPMN](https://img.shields.io/badge/BPMN-8250df?style=flat-square)](#-стек-и-инструменты)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](#-стек-и-инструменты)
[![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=swagger&logoColor=white)](#-стек-и-инструменты)
[![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)](#-как-устроен-контур)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](#-стек-и-инструменты)

</div>

---

## 👩🏻‍💻 обо мне

Сейчас работаю в **«Агроном-Саде»** в цифровой трансформации: производство, склад, логистика, master data и всё, что между ними начинает ломаться при попытке собрать единый контур.

До этого стажировалась в **WB.TECH**.

Целюсь в продуктовые команды — **mobile / B2C / subscriptions / e-commerce / FitnessTech**. Больше всего нравятся задачи, где за одной фичей быстро появляются состояния, интеграции, данные и несколько неприятных edge cases.

4 курс НИУ ВШЭ.

---

## 🧩 коммерческий опыт

| Зона | Что делала |
|:---|:---|
| **Внутренний продукт** | Разбирала ручные и Excel-процессы, собирала AS-IS / TO-BE и переводила это в требования к системе (роли, шаги, данные, проверки) |
| **ERP / WMS / TMS** | Описывала стыки между производством, складом и логистикой: где рождаются данные, кто ими владеет, куда они уходят и когда должны синхронизироваться |
| **Master Data** | Приводила к общей модели справочники сортов, участков, партий и операций: атрибуты, идентификаторы, дубли, mappings между источниками |
| **Интеграции** | Фиксировала состав обмена, источник / получателя, JSON / XML, контрольные точки, ошибки и повторную обработку |
| **Модели** | ERD для предметной области, UML для состояний / взаимодействий, BPMN для процессов и ручных разрывов |
| **BI / отчётность** | Формализовала требования к данным и витринам; отдельный кусок — ТЗ на дашборд «Паспорт сорта» |
| **Версионирование** | Git для технических артефактов: OpenAPI, PlantUML, SQL, mappings и служебные скрипты; feature-ветки → merge request → review → merge, релизные теги для согласованных версий |

---

## 🛠 стек и инструменты

<div align="center">

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/OpenAPI_/_Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=111111)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

**Данные:** PostgreSQL / SQL · Python / pandas  
**API и обмен:** REST / HTTP · JSON / XML · OpenAPI / Swagger · Postman  
**Асинхронщина:** RabbitMQ (очереди, retry / DLQ, идемпотентная обработка)  
**Моделирование:** UML / PlantUML · BPMN · ERD / IDEF1X  
**Версионирование:** Git / GitLab · branches · merge requests · tags

<details>
<summary><b>🏗 как устроен контур</b></summary>
<br>

Публично показываю его в обезличенном виде (часть технических деталей в портфолио реконструирована, без внутренней документации компании).

**Production Management** — производственный учёт: участок, сорт, операция, факт работ, сбор урожая.  
**ERP** — экономика / ресурсы / документы.  
**WMS** — партии, ячейки, остатки и перемещения.  
**TMS** — рейсы, транспорт и статусы доставки.  
**MDM** — канонические справочники и mappings между системами.  
**BI / DWH** — урожайность, качество, затраты и логистика.

Пример обычной цепочки: партия появляется в производственном контуре → уходит в WMS на приёмку → попадает в ERP как объект учёта → дальше используется в BI.

Для синхронных операций — **REST / OpenAPI**. Для событий между контурами — **RabbitMQ** (например, `harvest.batch.created`, `warehouse.lot.received`, `shipment.status.changed`).

Технические артефакты живут в Git: контракт API, PlantUML-схемы, SQL, mappings, служебные скрипты. Рабочая схема — короткие feature-ветки, MR с review, после согласования merge в основную ветку; стабильные версии помечаются тегами.

</details>

---

## 📂 портфолио

<div align="center">

[![SA Portfolio](https://img.shields.io/badge/→_SA_PORTFOLIO-1f6feb?style=for-the-badge&logo=github&logoColor=white)](https://github.com/spicerrr/sa-portfolio)

</div>

| Кейс | Фокус |
|:---|:---|
| **Смена / FitnessTech** | мобильная геймификация: session lifecycle, REST API, State Machine, ERD, продуктовые события, edge cases |
| **AgriTech / internal systems** | master data, ERP / WMS / TMS, интеграционные потоки, RabbitMQ, требования и модели данных |

---

## 🎓 учебные проекты ВШЭ

| Домен | Проект | Что внутри |
|:---|:---|:---|
| **Data Analytics / кино** | [**Sci-Fi Movies**](https://github.com/spicerrr/sci-fi-movies) | TMDb + OMDb, сбор и объединение данных, нормализация, EDA, проверка гипотез |
| **NLP / computational research** | [**Oscar × HdRezka**](https://github.com/spicerrr/oscar-rezka-comments) | 20k+ комментариев, стратифицированная выборка, локальная LLM-разметка, проверка и анализ |
| **Digital Media / data storytelling** | [**Reddit: восемь версий одного года**](https://github.com/spicerrr/reddit-2025-longread) | интерактивный дата-лонгрид, агрегирование данных, визуальная структура и веб-интерфейс |
| **Data Visualization / Fitness** | [**52 Days of GYM**](https://github.com/spicerrr/52-days-of-GYM) | интерактивная визуализация тренировочного цикла из логов Strong |

---

## ✉️ контакты

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:liza.spcr@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-spicerrr-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spicerrr)

</div>

---

<div align="center">

<sub>System Analysis · Business Processes · Digital Products</sub>

</div>
