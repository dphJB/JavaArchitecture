Разработка корпоративных систем на Java
===



Java World Overview
---
* Java, JVM
* Standarts, процесс развития Java
* J2SE, J2EE
* JBoss, Spring, J2EE - как основные столпы backend
* JVM как платформа: Groovy, Kotlin, Closure etc
* ПО разработки: Idea, Eclipse, JRebel, профайлеры и т.д.

Что такое архитектура
---
* Определения
* Управление сложностью по Макконнеллу
* Layers,Tiers
* SOA и другие популярные буковки
* Литература


Управление зависимостями в приложении
---
* Изолирование модулей, принципы контроля связности
* DIP: Dependency Inversion Principle
* Singletons: плюсы и минусы
* IoC фреймворки
** Зачем нужны аннотации в java
** Spring
** Picocontainer
** Guice
* Модули
** OSGi
** Eclipse RCP plugins
** Spring OSGi support
** Java 9
 
Работа с БД
---
* Основные архитектурные шаблоны: Table model, Active Record, ORM, UnitOfWork, DataTableGate
* JDBC
* Spring templates
* DAO temlates, CRUD
* OOOQ
* iBatis
* JPA, Hibernate
* H2DB - для тестирования
* NoSQL DB и Spring Data
* Управление транзакциями
  
Сериализация данных
---
* Standart serializaton
* Jackson
* XStream, Protobuf, Guava serialization

Логгирование
---
* Зачем оно нужно
* История логгинга в java: log4j, slf4j, logback
* Как анализировать
* Graphite, carbone
* MBeans

Web программирование
---
* Основные паттерны
** MVC
** Transaction commands
** Services
** single process/multi process architecture (IO vs NIO)
** Реактивное программирование
* Servlets
* JSP, Templates engines
* Spring MVC
* GWT
* Play! 
* Grails
* Tomcat, Jetty, Google AppEngine и другие веб-сервера
* REST
* Netty
* Akka 
* Commet
* Новые веяния: Ratpack, vert.x

Обмен сообщениями
---
* Шаблоны работы с сообщениями
* JMS
* JBoss groups
* Spring messaging
* сообщения через БД

Прочие важные элементы
---
* Security
** Spring Security
** OAuth, OAuth 2.0
* Business rules
** BPM как идеология
** JBoss Steam, Spring BPM etc

Производительность
---
* Cache
** HashMap
** EhCache
** Terracota
* Коллекции примитивов
* JNI
* Unsafe memory
* Профайлинг
* Perflog и мониторы
* Как работать с Garbage Collector

Инструментарий
---
* JRebel
* FreBug and code inspections
* Ant, Mavem, Grails, Ivy, KAnt
* WebDriver

Экзотика
---
* Scripting: Rhino, Groovy
* Kotlin
* ASM
