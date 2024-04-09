---
title: Абстракция
status: Completed
category: Property
tags: ["fundamental", "", ""]
---

В контексте вычислительной техники абстракция — это представление, 
которое скрывает специфику реализации от потребителя [сервисов](/service/) 
(потребителем является компьютерная программа или человек), 
делая систему более простой и понятной.
Хороший пример — операционная система (ОС) компьютера.
Она абстрагирует все тонкости работы компьютера.
Пользователю не нужно ничего знать о процессоре, памяти и работе с программами: 
он просто управляет операционной системой, а та разбирается со всеми нюансами.
Все они скрыты за «занавесом» ОС или абстракцией.

Системы, как правило, имеют несколько уровней абстракции.
Это значительно упрощает разработку.
При программировании разработчики создают компоненты, совместимые с определенным уровнем абстракции, 
и не заботятся о том, как та или иная функциональность реализована на нижележащих уровнях.
Достаточно того, что эти компоненты работают с определенным уровнем абстракции. 
А то, что у него скрыто «под капотом», не имеет значения.