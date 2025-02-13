# Резюме

Акинин Олег

37 лет, родился 10 августа 1987

- Проживаю: Санкт-Петербург
- Желаемая должность: Тимлид, руководитель разработки
- Занятость: Проектная работа/Полный день
- График работы: удаленная работа, гибкий график

## Контакты

- Телефон: +7-(999)-495-29xx
- Telegram: https://t.me/kicumkicum
- Mail: kicumkicum@gmail.com
- LinkedIn: http://linkedin.com/in/kicumkicum
- GitHub: https://github.com/kicumkicum

## Рабочий опыт

Опыт профессиональной деятельности: 11 лет

Опыт трудовой деятельности: 16 лет

### [BSS Bank Soft System](https://bssys.com) Санкт-Петербург

Март 2021 — настоящее время

Архитектор фронтенд продуктов, web и мобильные приложения

Стек: React; Redux; TypeScript; LLM; OpenAI API; LangChain; LangGraph; LangFuse; OpenAI API; Styled Components; Cordova; Node.js; jest; cordova, StoryBook; Gitlab CI/CD; TeamCity; Docker; etc.

Основные обязанности:

- Разработка и улучшение архитектуры проектов, всего их порядка 10;
- Написание документации
- Оценка и планирование трудозатрат;
- Декомпозиция задач;
- Описание архитектурных решений, ADR;
- Консультации аналитиков, продуктов по технической части;
- Фиксирование тех долга;
- Созвоны с заказчиками;
- Настройка инфраструктуры проекта: webpack, eslint, react-test-library, storybook, GitLab CI/CD, TeamCity CI/CD;
- Код-ревью.

Достижения:

- Реализации работы с [Биометрией](https://ebs.ru/citizens/) в приложении
  - Сложная, с точки зрения интеграции, доработка;
  - Спроектировал и реализовал;
  - Общался с заказчиком и интегратором для отладки. Приходилось объяснять заказчику, что проблема на его стороне, а не в приложении.
- Реализация работы с [Цифровым Рублем](https://www.cbr.ru/fintech/dr/) в приложении
  - Адаптировал Альбом сообщений Цифрового Рубля для работы на фронте. Альбом представляет собой контракты в виде XSD (XML) схем для запросов и ответов. Некоторые объекты для них занимают около 100 строк кода. Всего в Альбоме 110+ документов. Для удобной работы с ним я подготовил инструменты, для конвертации XSD схем в TypeScript типы. Полученные типы были интегрированы в JS приложение в виде небольшого TS слоя. При передаче объекта невалидной структуры разработчик видит проблемы сразу в редакторе и на CI/CD;
  - Так же реализована рантайм-валидация передаваемых значений с помощью jsonschema (TS не поддерживает сложные паттерны сток, а jsonschema поддерживает);
  - В последствии произвел обновление на новую версию Альбома с возможностью выбирать в коде, с какой версией альбома работать.
- Запуск редизайна основного приложения
  - Поменял стандартные процессы в команде под более эффективные в данном случае;
  - Определил стек и решения, которые будем применять;
  - Разработал план, как небольшой командой разработки обновить большое приложение с 10 летней историей и не умереть;
  - Контролировал процесс и результат.
- Запустил инициативу и процесс по внедрению бест практикс работы с секретами в коде и CI/CD на уровне компании;
- Участвовал в экспертном совете по разработке единой мобильной платформы на уровне компании. В рамках нее был определен технологический стек и технологические особенности будущей платформы;
- Разработал VK Teams бота для доступа к ChatGPT. Придумал, запрограммировал, развернул на сервере в docker контейнере с маршрутизацией через proxy-сервер. Настроил автобилд и автодеплой. Для реализации на typescript, с помощью LLM сконвертировал python sdk vk teams в версию на typescript;
- Реализовал микрофреймворк для работы с LangGraph, существенно упрощающий написание сценариев.

### [Teacher Army](https://teacher.army) Санкт-Петербург, Хобби-проект

Декабрь 2021 — настоящее время

Основатель, Технический директор

Стек: TypeScript; React; Next.js; Node.js; MongoDB; jest; Telegram API; Google API; GitHub API; Яндекс.Облако; GitHub Actions CI/CD; Vercel; Google Cloud; Google Workspace; etc.

Основные обязанности:

- Продуктовое развитие;
- Техническое развитие;
- Маркетинг и продвижение;
- Построение команды и процессов;
- Онбординг новых сотрудников;
- Написание документации и инструкций;
- Проектирование архитектуры;
- Выбор инфраструктуры;
- Код-ревью;
- Делегирование;
- Администрирование и юридические вопросы;
- Общение с заказчиками.

Достижения:

- Превратил идею в план и вывел хобби проект в продакшен;
- Уместил все дела по проекту в свободное время;
- Организовал процесс и технические требования таким образом, чтобы разработчик уровня джун мог запрограммировать рабочую и поддерживаемую систему;
- Решил проблемы проекта, связанные с санкциями и уходом зарубежных сервисов из РФ;
- Спроектировал бекендную часть Next.js-проекта в функциональном и декларативном стиле. Это существенно упростило создание API;
- Спроектировал концептуальное решение взаимосвязи между фронтом и беком на основе контрактов, ООП и строгой типизации TypeScript. Это существенно упростило добавление новых доменных сущностей, реализацию бизнес-логики и взаимодействие фронта и бека;
- Провел стажировку четверых стажеров в течении 2х месяцев. Разработанный и примененный мною процесс позволил без особых усилий с моей стороны в короткий срок ввести в проект ребят без продакшен опыта, и они смогли реализовать продуктовые фичи;
- Разработал систему Схема БД <-> Типы <-> Валидация <-> Контроллеры, связанную единой системой TypeScript типов. Правишь схему и видишь, что у тебя посыпалось;
- Спроектировал и описал технические требования модуля "Технические работы", который должен корректно и закрывать все страницы, API роуты и ответы Телеграм бота ответом о проведении технических работ. Провел ревью и приемку. Можно предположить, что это рядовая функциональность и удивиться, почему она в достижениях, но в этом вся соль. Фича выглядит минорной, реализовать ее нужно как можно раньше. И пусть воспользоваться ей придется парой раз в год, в случае поломки можно показать понятное и симпатичное сообщение, а не белую страницу;

### [Siemens](https://www.siemens.ru) Санкт-Петербург

Ноябрь 2020 — Март 2021 5 месяцев

Инженер-исследователь, Team-lead

Стек: React; Redux; Angular; Node.js; jest; TeamCity; etc.

- Разработка плана перевода проекта с Angular.js на React
- Улучшение кодовой базы и инфраструктуры проекта (линтинг, тесты)
- Наставничество
- Код-ревью

Достижения:

- Реализовал инструмент по конвертации компонентов Angular 1.6 в React в рамках перехода проекта с Angular на React

### [Okko](https://okko.tv) Санкт-Петербург

Июль 2020 — Октябрь 2020 4 месяца

Ведущий разработчик

Стек: React; Redux; TypeScript; VanillaJS; jest; TeamCity; etc.

Основные обязанности:

- Разработка двух SmartTV приложений под несколько платформ
- Код-ревью
- Проектирование

Достижения:

- Внедрил в рабочий процесс написание unit-тестов
- Внедрил запуск тестов в StoryBook'е
- Реализовал модуль для unit-тестирования HTML5Video плеера

### [HtmlAcademy](https://htmlacademy.ru) Санкт-Петербург

Сентябрь 2018 — Июль 2020 1 год 11 месяцев

Автор курсов по программированию, лид

Стек: React; Redux; VanillaJS; Node.js; TypeScript; jest; GitHub Actions; Google Cloud; etc.

Основные обязанности:

- Разработка новых курсов, поддержка существующих;
- Менеджмент дизайнеров, верстальщиков учебных проектов;
- Написание ТЗ. Программирование проектов. Разработка инструментов;
- Чтение лекций;
- Взаимодействие с пользователями.

Достижения:

- Прочитал порядка 50 онлайн-лекций по JS, React, Node.js и проектированию веб приложений;
- Разработал систему шаблонизации и генерации текстов домашних заданий для нескольких учебных проектов;
- Спроектировал систему автотестирования домашних заданий;
- Разработал с нуля 2 учебных курса (темы, программа, задания, учебные проекты, демонстрационный проект) в составе команды авторов.

### [SPBTV](https://ru.spbtv.com) Санкт-Петербург

Март 2018 — Сентябрь 2018 7 месяцев

Web-разработчик

Стек: React; Redux; Node.js; Flow; jest; TeamCity; etc.

Основные обязанности:

- Разработка SmartTV приложения под несколько платформ
- Код-ревью
- Проектирование

Достижения:

- Внедрил статическую типизацию на базе flow

### [Interfaced](https://interfaced.tv) Томск

Январь 2013 — Март 2018 5 лет 3 месяца

Web-разработчик, Team-lead

Стек: VanillaJS; Node.js; Google Closure Compiler; ZombieBox; SmartTV; TypeScript; mocha; chai; etc.

Основные обязанности:

- Заказная разработка SmartTV приложений
- Управление кросс-функциональной распределенной командой (8 человек)
- Организация рабочего процесса
- Написание кода
- Код-ревью
- Декомпозиция продуктовых-задач
- Организация неформальных мероприятий
- Закупка всего необходимого для команды в обозначенный бюджет
- Проведение ретроспектив

Рабочие проекты:

- Имплементация абстракций-адаптеров для работы фреймворка ZombieBox с различными SmartTV платформами (Tizen, WebOS, Orsay, Eltex, Dune, etc)
- Сопровождение репозиториев этих абстракций: подготовка релиза, ревью кода, составление roadmap
- Persik.tv - SmartTV приложение для просмотра ТВ и VOD - поддержка и добавление новых фич
- Виртуальные окна Kaleva - программно-аппаратное решение для объединения нескольких ТВ в "видео стену"
- Dom.ru 2.0 - SmartTV портал для просмотра ТВ, VOD, контента с внешних устройств и тд - поддержка и реализация новых фич, планирование спринтов, внедрение Scrum

Достижения:

- Вырос в компании от джуна до тимлида
- Упростил разработку на STB с помощью создания инфраструктуры виртуальных машин
- Поменял рабочий процесс с хаусоподобного (у нас) водопада на Scrum
- Создал с нуля программно-аппаратное решение на базе Linux для проекта Kaleva. Очень нетипичная задача для фронтендера) Фронтенд там тоже был нужен, но это только 5% от общего количества трудозатрат
- Повысил производительность и отзывчивость приложения на очень слабом устройстве с 5сек до 0.8сек
- Перевел процесс разработки с gitflow на rebase flow
- Форсировал переход в компании с mercurial на git

## Обо мне

Я люблю программировать, взаимодействовать с людьми, менторить и воодушевлять их. А также создавать интересные и полезные продукты. Поэтому жду от работы задач в этих областях. Мне нравится реализовать бизнес-задачи, сохраняя и повышая качество кодовой базы. Люди - главная ценность, поэтому я стараюсь поддерживать дружную атмосферу в команде, развивать ответственность и компетенции всех участников, чтобы разработка двигалась вперёд быстрее и быстрее.

Мне нравится развивать продукт, выстраивать процессы, упрощать коммуникацию, а так же воодушевлять коллег на подвиги и свершения. Обладаю выдержкой для получения результата даже в самых пожароопасных ситуациях. Если у вас есть годный проект или планы по его созданию, то давайте реализуем их вместе!

Личные качества:

- Сфокуссированность на результате, а не ритуалах
- Умение просить помощи у тех, кто больше разбирается в вопросе
- Умение найти того, кто разбирается в вопросе
- Умение делегировать
- Ищу компромисс между качеством и скоростью
- Умение построить удаленную распределенную команду и удобный и эффективный процесс
- Работаю на удаленке

Личные достижения:

- Провел более 200 интервью разработчиков и более 300 консультаций в качестве ментора;
- Довел петпроект до продакшена;
- ~~Не перегораю~~ Перегораю, но знаю, что делать с этим состоянием, как выходить из него и продолжать эффективно работать;

### Рабочие проекты

- Имплементация абстракций-адаптеров для работы ZombieBox с различными SmartTV платформами
- Сопровождение репозиториев этих абстракций: подготовка релиза, ревью кода, составление roadmap
- Persik.tv - SmartTV приложение для просмотра ТВ и VOD - поддержка и добавление новых фич
- [Виртуальные окна Kaleva](https://www.youtube.com/watch?v=xpBx2IuuWR0) - программно-аппаратное решение для объединения нескольких ТВ в "видео стену"
- [Dom.ru 2.0](https://djhooligantk.livejournal.com/653410.html) - SmartTV портал для просмотра ТВ, VOD, контента с внешних устройств и тд - поддержка и реализация новых фич, планирование спринтов, внедрение Scrum'а
- SPBTV - приложение для просмотра ТВ и VOD-контента
- [Digital2Retail](https://bssys.com/products/digital2financial-management/d2retail/) - банковский веб-клиент и мобильное приложение для работы физ лиц
- [Digital2SME](https://bssys.com/products/small-business/digital2-sme/) - веб-клиент онлайн банка для работы корпоративных клиентов

### Некоторые домашние проекты

- [Teacher Army](https://teacher.army) - сервис поиска наставника по программированию. Сайт и телеграм боты [@TeacherArmyBot](https://t.me/TeacherArmyBot) и [@nikolay_robotov_ta_bot](https://t.me/nikolay_robotov_ta_bot)
- https://github.com/kicumkicum/stupid-player - middleware для создания аудио-плеера, выполняющее всю грязную работу со звуком в node.js
- https://github.com/torrent-proxy/bt-stream - torrent-качалка на нодовксих стримах (node.js stream)
- https://github.com/kicumkicum/bond - расширение для Хрома, связывающий тикеты в Redmine с пулл-реквестами и ветками в Bitbucket

Другие проекты так же можно посмотреть на https://github.com/kicumkicum и https://github.com/torrent-proxy

### Контакты

- Телефон: +7-(999)-495-29xx
- Telegram: https://t.me/kicumkicum
- Mail: kicumkicum@gmail.com
- LinkedIn: http://linkedin.com/in/kicumkicum
- GitHub: https://github.com/kicumkicum

## Образование

- Неоконченное высшее
- Национальный исследовательский Томский государственный университет, Томск, 2007
- ФПМК, Прикладная информатика (по областям)

### Знание языков

- Русский — Родной
- Английский — B2 — Средне-продвинутый

### Навыки

JavaScript; Scrum; Atlassian Jira; Mercurial; ООП; HTML5; Веб-программирование; Web Application Development; Teamleading; Agile Project Management; Git; HTTP; Smart TV; TypeScript; Google Closure Compiler; Node.js; Linux; Bash; React; Redux; Redux Toolkit; Next.js; express; CI/CD; TDD; React Testing Library; Enzyme.
