Роль `vpc.publicAdmin` предоставляет доступ к управлению публичными IP-адресами и внешней связностью.

Пользователи с этой ролью могут создавать и удалять публичные IP-адреса, а также управлять внешней связностью. 

Включает разрешения, предоставляемые ролью `vpc.viewer`.

Можно назначить на облако или каталог. Важно: если сеть и подсеть находятся в разных каталогах, то наличие роли `vpc.publicAdmin` проверяется на том каталоге, в котором находится сеть.