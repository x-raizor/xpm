---
description: Типовые конфигурации применения элементов и их соединений
---

# Типовые соединения

Как в языке разные слова, скомбинированные определённым образом, могут выражать одно и то же значение, так и разные комбинации элементов графической нотации могут решать одну и ту же задачу. На схемах для описания схожих ситуаций также могут использоваться разные подходы. В этом разделе приведены шаблонные приёмы решения стандартных ситуаций.

## Cтарт и течение

<div align="left">

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Линейный путь с опциональными точками. Вторая точка необязательна, что равносильно возможности перепрыгнуть через неё</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Безусловное разветвление и схождение</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (3) (1) (1).png" alt=""><figcaption><p>Многовариантный старт от событий</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption><p>Многовариантный старт через ключевые точки</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (5) (1).png" alt=""><figcaption><p>Использование событий для повторных вхождений в фрагменты процесса</p></figcaption></figure>

</div>



## Ветвления

<div align="left">

<figure><img src="../.gitbook/assets/image (6) (1).png" alt=""><figcaption><p>Ветвление событиями</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (7) (1).png" alt=""><figcaption><p>Ветвление триггером</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>Ветвление таблицей решений (decision table)</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption><p>Цикл</p></figcaption></figure>

</div>



## Взаимодействия

<div align="left">

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Петля взаимодействия «пинг-понг»: посыл, отработка, получение результата</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption><p>Синхронизация ключевых точек на разных дорожках, взаимодействуют оба актора</p></figcaption></figure>

</div>

Например, это услуга покупки в «каменном» магазине. Главная линия ведётся покупателем (Актор 1). Он входит в магазин, Актор 2 вовлекается в коммуникацию с ним, откликаясь на запрос. Когда потребитель покидает магазин и наслаждается купленным в следующей точке, Актора 2 и нашей роли уже нет.



<div align="left">

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption><p>Совместные ключевые точки на дорожке одного участника. Маркирует начало совместных точек до следующего указания участников. В примере во второй точке подключается Актор 2, а третья точка вновь относится только к Актору 1</p></figcaption></figure>

</div>



## Навигация по карте

<div align="left">

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption><p>Разметка карты группирующими этапами. Обычно выполняется наверху карты на дорожке ведущего актора</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p>Использование значимых событий как маркеров для ориентации в пространстве карты</p></figcaption></figure>

</div>
