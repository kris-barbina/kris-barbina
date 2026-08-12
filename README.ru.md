<h1 align="center">Кристина Барбина</h1>

<p align="center">
  <b>Backend-разработчик · интеграционная архитектура</b><br>
  Java 21 · Spring Boot 3 · PostgreSQL · RabbitMQ · Docker
</p>

<p align="center">
  <a href="https://gitlab.com/kris.barbina"><img alt="GitLab" src="https://img.shields.io/badge/%D0%BA%D0%BE%D0%B4-GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white"></a>
  <a href="https://1dh.ru/"><img alt="DataHUB" src="https://img.shields.io/badge/%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82-DataHUB-2E7D32?style=flat-square"></a>
  <a href="https://www.linkedin.com/in/kristina-barbina/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:kris.barbina@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://t.me/KristinaBarbina"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white"></a>
</p>

<p align="center"><sub><a href="README.md">🇬🇧 In English</a></sub></p>

---

### 👋 Код лежит на GitLab

Я делаю **DataHUB** — коммерческую интеграционную платформу. Репозитории, пайплайны и ревью живут на GitLab: **[gitlab.com/kris.barbina](https://gitlab.com/kris.barbina)**. Поэтому здесь пустой график коммитов — работа идёт, просто в другом месте. Код и архитектуру покажу на собеседовании.

### 🚏 DataHUB — шина данных для 1С:Предприятие

[1dh.ru](https://1dh.ru/) · [docs.1dh.ru](https://docs.1dh.ru/)

Платформа для интеграции 1С с остальным корпоративным ландшафтом: событийный обмен вместо россыпи точечных выгрузок.

|  |  |
|---|---|
| **Моя роль** | Автор архитектуры и единственный backend-разработчик, руководитель продуктовой команды (4 человека) |
| **Ядро** | Java 21, Spring Boot 3.5, Spring MVC, Data JPA / Hibernate, PostgreSQL |
| **Обмен** | RabbitMQ — at-least-once, идемпотентные обработчики, retry, фиксация состояния и восстановление после сбоев |
| **Безопасность** | Собственный сервер авторизации (OAuth2), сессии на JWT, TLS/mTLS на внешнем контуре (Nginx) |
| **Поставка** | Docker / Compose, GitLab CI/CD (свои пайплайны), Jib на Temurin 21, миграции Flyway, собственный release-builder для on-prem |
| **Качество** | JUnit 5, Testcontainers, WireMock, SonarQube, JaCoCo |
| **Где работает** | Два внедрения на серверах заказчиков, SaaS-версия выходит на рынок, продукт готовится к включению в реестр российского ПО |

Архитектура родилась в 2020 году на проекте учётной системы для вуза (событийный обмен через RabbitMQ, файлы в S3), потом была переписана с нуля в самостоятельный Java-продукт — активная разработка с января 2023.

### 🧭 Что умею

- **Довожу backend от архитектуры до продакшена** — проектирование, код, тесты, пайплайны, релизы, которые потом эксплуатируют заказчики.
- **Проектирую интеграции** между разнородными корпоративными системами: контракты сообщений, идемпотентность, обработка сбоев, наблюдаемость.
- **Ставлю инженерные процессы** — статический анализ, автотесты, конфигурации и развёртывание как код, воспроизводимые релизы.
- **Знаю корпоративный домен** — 19 лет в enterprise-ИТ: ERP, финансы, склад, документооборот, производство; контуры на 500+ пользователей.

### 🧰 Стек

**Backend** — Java 21 · Spring Boot 3 · Spring MVC / WebFlux · Spring Security (OAuth2, JWT) · Hibernate / JPA · Gradle
**Данные и обмен** — PostgreSQL · MS SQL · RabbitMQ · Flyway · Caffeine · Bucket4j · S3-совместимые хранилища
**Инфраструктура** — Docker и Compose · GitLab CI/CD · Jib · Nginx (reverse proxy, mTLS) · Prometheus · Grafana (Loki, Mimir, Alloy)
**Тесты и качество** — JUnit 5 · Testcontainers · WireMock · JaCoCo · SonarQube
**Было раньше** — C# / .NET, ASP.NET · платформа 1С, 15+ лет на архитектурном уровне

### 🗂 Опыт коротко

- **2023 → сейчас — DataHUB** — собственный продукт: архитектура и весь backend.
- **2023–2026 — «Смарт Бэттериз» (группа «Энергон»), технический архитектор** — интеграционная архитектура производственной группы при переходе с иностранного ПО на 1С; регламент разработки и процессы Scrum/Kanban, статанализ кода 1С через SonarQube, дымовые тесты на Vanessa Automation, стек мониторинга (Prometheus, Grafana, Loki, Mimir, Alertmanager), GitLab CI/CD и инфраструктура как код, аудит производительности и переработка кластера 1С.
- **2020–2021 — «ВИКТОРИЯ СОФТ», главный архитектор проекта** — новое учётное ядро и портал для крупного вуза: нормализация объектной модели, двухуровневая схема фронт/бэк, около 15 интеграций, событийный обмен через RabbitMQ, файлы в S3. Отсюда выросла архитектура DataHUB.
- **2017–2020 — AXELOT, руководитель отдела внутренней автоматизации** — методики финансового учёта в ERP, портал сопровождения клиентов с интеграцией в ERP, учёт ВЭД, запуск ЭДО, планирование загрузки сотрудников и расчёт мотивации; администрирование 1С на 500+ пользователей.
- **2010–2013 — «Техно пульс»** — собственный интернет-магазин, от запуска до операционного управления.

### 📬 Что рассматриваю

Backend и интеграции на Java/Spring, роли интеграционного и solution-архитектора — удалённо, по договору или в штат.

**[kris.barbina@gmail.com](mailto:kris.barbina@gmail.com)** · [Telegram](https://t.me/KristinaBarbina) · [LinkedIn](https://www.linkedin.com/in/kristina-barbina/) · [GitLab](https://gitlab.com/kris.barbina) · [Резюме на hh.ru](https://hh.ru/resume/f34402a6ff10d5fd100039ed1f474353693034)
