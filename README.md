# Вопросы для аттестации с junior на middle python-разработчика (under construction)


Понятное дело, кроме знания что же это такое надо еще знать когда применять или не применять.
На миддла надо суметь ответить на какой-то __процент?__ тем.


ОБЩАЯ ТЕОРИЯ
===============================
- типы данных, структуры данных, алгоритмы
- оценка сложности алгоритмов (big O)
- модель памяти (стек/куча)
- динамическая типизация vs статическая
- ООП, на чём основано и когда им удобно пользоваться (+паттерны)
- императивный и декларативный стиль (куда отнести функциональное?)
- что такое SOLID
- асинхронная концепция программирования
- асинхронная концепция vs многопоточная концепция
- что такое MVC


ПИТОН
===============================
- плюсы-минусы
- GIL
- garbage collector (gc)? В чём его плюсы и минусы?
- модель памяти
- типы данных, структуры данных, алгоритмы
структуры - какие из них являются mutable/immutable? где будет быстрее поиск: dict, list, set, tuple?
- что нового в последних версиях
- Метаклассы
- Что такое генератор? Чем он отличается от итератора?
- дескрипторы, декораторы
- что такое WSGI и зачем он появился
- Что Вы знаете о Threading. Threading vs Multiprocessing
- Что такое async/await, для чего они нужны и как их использовать?
- как устроены фреймворки Flask или Django
- какие ещё есть знакомые фреймворки


ТЕСТЫ + CI/CD
===============================
- виды тестов: юнит-тесты, интеграционные тесты, приёмочные тесты и т.д.
- Как тесты и TDD влияют на организацию кода?
- Что такое mocking
- Что такое Code Debt и как с ним быть?
- Какие системы контроля версий Вы знаете?
- Что такое Git Flow?
- Что такое Git Rebase?
- Что такое Git Cherry pick?
- Что такое форсированный push?
- Что такое precommit check?
- Что такое code cohesion & code coupling?
- Если у вашего кода плохая организация, как вы это поймёте?


ЛИНУКС, СЕТИ и ТД
===============================
- что такое процесс и как он “живёт” в ОС
- что такое streams (в bash и тп)
- что такое сокеты и зачем они нужны
- виртуализация: какие бывают типы

- Иметь представление о том, как устроен стек протоколов TCP/IP.
- Что такое HTTP? Какие у него есть методы?
- Чем отличаются HTTP и HTTPS?
- Что такое REST?
- Что такое куки? Зачем они, как с ними работать и где они сохраняются?
- Может ли сервер изменить (добавить, удалить) куки?
- Что такое JWT (JSON Web Token)?
- Какие плюсы-минусы у микросервисов? У монолита?



БАЗЫ
===============================
- отличие PostgreSQL от MongoDB от ClickHouse и тд
- Как вы объясните всплеск интереса к NoSQL в последнее время?
- Как в SQL/NoSQL решаются проблемы масштабируемости?
- В каком случае вы предпочтёте документоориентированную СУБД вроде MongoDB вместо реляционной СУБД, такой как MySQL или PostgreSQL?

реляционная модель
- Atomicity, Consistency, Isolation, Durability (Атомарность, Согласованность, Изолированность, Устойчивость)
- нормализация (3 нормальная форма) / денормализация
- транзакции
- уровни изолированности транзакций
- вложенные транзакции
- курсоры
- NULL | NOT NULL
- статистика / индексы (составные, фильтрованные и тд) 
- хранимые процедуры, триггеры
- планы запросов
- партиционирование
- Что такое VACUUM в PostgreSQL?
- Что такое EXPLAIN? Какая разница между ним и EXPLAIN ANALYZE?
- Как вы обнаружите в приложении самые затратные запросы?

