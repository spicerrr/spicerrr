<div align="center">

# привет! ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif) я лиза

### Junior System Analyst

**B2C / mobile · интеграции · master data · бизнес-процессы**

[![System Analysis](https://img.shields.io/badge/System_Analysis-1f6feb?style=flat-square)](#-что-реально-делаю-в-цт)
[![BPMN](https://img.shields.io/badge/BPMN-8250df?style=flat-square)](#-стек-и-инструменты)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](#-стек-и-инструменты)
[![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=swagger&logoColor=white)](#-стек-и-инструменты)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](#-стек-и-инструменты)

</div>

---

## 👩🏻‍💻 обо мне

Сейчас работаю в **«Агроном-Саде»** в контуре цифровой трансформации: разбираю процессы и данные вокруг производственного учёта, склада и логистики, формализую требования к внутренним системам и привожу в порядок master data. Раньше стажировалась в **WB.TECH**.

Целюсь в продуктовые команды — в первую очередь **mobile / B2C / subscriptions / e-commerce / FitnessTech**. Нравятся задачи, где «добавить одну фичу» быстро превращается в состояния, интеграции, данные и несколько неприятных edge cases.

4 курс НИУ ВШЭ.

---

## 🧩 что реально делаю в ЦТ

| Зона | Мой кусок |
|:---|:---|
| **Внутренний продукт** | Разбираю ручные и Excel-процессы, собираю AS-IS / TO-BE, превращаю это в требования к системе (кто, что, когда вводит и что должно происходить дальше) |
| **ERP / WMS / TMS** | Работаю на стыках контуров: какие данные где рождаются, кто ими владеет, куда они уходят и в какой момент должны синхронизироваться |
| **Master Data** | Справочники сортов, участков, партий и операций: канонические сущности, атрибуты, идентификаторы, дубли и mapping между источниками |
| **Интеграции** | Описываю состав обмена, источник и потребителя данных, форматы JSON / XML, контрольные точки и ошибочные сценарии |
| **Модели** | ERD + UML для сущностей, состояний и взаимодействий; BPMN для процессов и ручных разрывов между ролями / системами |
| **BI / отчётность** | Формализую требования к данным и витринам; отдельный кейс — ТЗ на дашборд «Паспорт сорта» |
| **Передача в разработку** | Требования, схемы, сценарии и проверки; стараюсь доводить задачу до состояния, когда разработчику не нужно угадывать бизнес-логику |

---

## 🛠 стек и инструменты

<div align="center">

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/OpenAPI_/_Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=111111)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

**Данные:** PostgreSQL / SQL · Python · Jupyter · pandas  
**API:** REST / HTTP · JSON / XML · OpenAPI / Swagger · Postman  
**Моделирование:** UML · PlantUML · BPMN · ERD  
**Версионирование:** Git / GitHub — ветки, коммиты, rebase / push, версионирование кода и документации в собственных проектах

<details>
<summary><b>📎 что скрывается за «внутренними системами»</b></summary>
<br>

Это не один монолит. В моей зоне — производственный контур и его стыки с **ERP / WMS / TMS**, качеством и BI.

Например, одна партия урожая проходит через несколько систем: появляется в производственном учёте, дальше становится объектом складского учёта в WMS, попадает в экономический контур ERP и потом — в аналитику. На каждом стыке важно не только «передать поле», а договориться, **что это за сущность, какой у неё ID, где source of truth и что делать, если данные в двух источниках разъехались**.

Мой кусок здесь — в основном смысл и контракты данных: сущности, атрибуты, ownership, mappings, сценарии обмена и ручные исключения. Архитектуру корпоративных систем в публичный GitHub не выношу; для портфолио такие задачи реконструирую на обезличенной модели.

**Про Git:** в «Агроном-Саде» основной рабочий контур — Google Docs / Sheets и корпоративные документы, поэтому Git не был source of truth для требований. Git / GitHub у меня уже нормально используется в собственных технических проектах — с историей изменений, ветками и версионированием кода / документации.

</details>

---

## 📂 портфолио

<div align="center">

[![SA Portfolio](https://img.shields.io/badge/→_SA_PORTFOLIO-1f6feb?style=for-the-badge&logo=github&logoColor=white)](https://github.com/spicerrr/sa-portfolio)

</div>

Здесь оставляю только то, что релевантно системному анализу: требования, процессы, API, модели данных, состояния, интеграции и тестовые сценарии.

**Сейчас собираю два основных кейса:**

| Кейс | Что показываю |
|:---|:---|
| **Смена / FitnessTech** | мобильная геймификация: session lifecycle, REST API, State Machine, ERD, продуктовые события и edge cases |
| **AgriTech / internal systems** | обезличенная реконструкция коммерческого контура: master data, ERP / WMS / TMS, интеграционные потоки и требования |

Исследовательские и медиапроекты остаются отдельными репозиториями — в SA-профиле их не дублирую.

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
