# Определение перспективного тарифа для телеком компании

## Задача

Заказчик — оператор сотовой связи. Чтобы скорректировать рекламный бюджет, нужно проанализировать поведение клиентов и сделать вывод, какой тариф приносит компании больше средств. 

## Данные

Входные данные от компании: 

данные о 500 пользователях за 2018 год, содержащие сведения о возрасте, городе проживания, каким тарифом клиент пользуется, сколько звонков совершает, сколько отправляет сообщений и использует интернет-траффика. 

## Выводы

Исследованы данные по каждому тарифу. В среднем, клиентам нужно около 460 минут разговора, 45 смс и 17 гб в месяц.

По тарифу smart выручка, полученная по абонентской плате, примерно равна выручке за услуги не включенные в абонентскую плату. По тарифу ultra переплат сверх тарифа меньше, 40% от оплаты по тарифу. Не используют звонки 1,4% клиентов, не используют смс-сообщения 15.5% клиентов, не используют интернет 0.4% клиентов.

Проверка гипотез с применением статистических тестов показала, что средняя выручка от пользователей тарифов ultra и smart отличается и средняя выручка от пользователей тарифов ultra больше smart, а средняя выручка пользователей из Москвы близка выручке пользователей из других регионов.

Тариф ultra выгоднее для компании, чем тариф smart. Клиентов ultra в 2,3 раза меньше, чем клиентов smart, но выручки они приносят меньше всего в 1,4 раза

## Инструменты и навыки 
*pandas*, *Matplotlib*, *NumPy*, *SciPy*, *описательная статистика*, *проверка статистических гипотез*
