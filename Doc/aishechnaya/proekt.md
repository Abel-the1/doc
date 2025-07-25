---
order: 3
title: API design hub
---

🎯 Цель

Создать удобную и централизованную среду, которая поможет внедрению API first в команды и сделает его проще и понятней.

📈 Основная функциональность

Кейсы

\- Команды вручную пишут и редактируют OpenAPI

\- Получают моментальную автодополнение, валидацию и линтинг

\- Могут обсудить и согласовать контракты до разработки

Функции

1\. Визуальный редактор OpenAPI со smart-подсказками ()

2\. Интеграция с реестром reusable-компонентов. Встроенный каталог schemas, parameters, responses, securitySchemes. Возможность вставить \$ref в 1 клик, с автокомплитом. Поиск и предпросмотр reusable-компонента перед вставкой

3\. Генерация примеров (examples) На основе описания полей и названия схем • Возможность сгенерировать пример вручную или автоматически на основе schema + описания

4\. AI-помощник. Отвечает на вопросы по OpenAPI: “как описать пагинацию?”, “как сделать OAuth2?” • Может сгенерировать фрагмент спецификации по текстовому описанию: “Добавь GET /accounts с query-параметром clientId и ответом 200 со списком счетов”

5\. Предпросмотр и экспорт. Live-просмотр документации в docusaurus, публикация на порталы, экспорт в gitlab.

🧩 Этапы реализации

1\. Reusable-компоненты. Стандартные описания ошибок, куски схемы, которые можно переиспользовать

2\. Генерация примеров. Сервис примеров

3\. AI помощник

4\. Полноценный редактор