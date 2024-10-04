* `{{ ui-key.yacloud.smart-web-security.arl.label_rule-without-grouping }}` — считать каждый запрос по отдельности.
* `По характеристикам` — считать группы запросов, объединенных одной или несколькими характеристиками. 

    * Выберите характеристику для группировки:

        Автоматическая группировка | Группировка по ключу
        ---|---
        `Request path` — путь запроса | `HTTP cookie` —  строка в заголовке cookie
        `HTTP method` — метод запроса | `HTTP header` — строка в заголовке HTTP
        `IP-адрес` — IP-адрес, с которого пришел запрос | `Query params` — строка в параметрах запроса.
        `Регион` — регион, которому принадлежат IP-адреса запросов |
        `Host` — домен, на который пришел запрос |

        Для группировки по ключу, укажите значение ключа.

    * (Опционально) Включите опцию `Учитывать регистр`, чтобы характеристики с одинаковыми значениями, но в разном регистре попадали в разные группы.

Задайте лимит запросов или лимит запросов на группу, а также временной интервал (от `1 секунды` до `60 минут`), за который рассчитывать лимит. Все запросы сверх лимита будут блокироваться.