Роль `managed-kafka.admin` позволяет управлять кластерами Apache Kafka® и просматривать их логи, а также получать информацию о квотах и операциях с ресурсами сервиса.

Пользователи с этой ролью могут:
* управлять доступом к кластерам Apache Kafka®;
* просматривать информацию о [кластерах Apache Kafka®](../../managed-kafka/concepts/index.md), а также создавать, изменять, удалять, запускать и останавливать их;
* просматривать логи работы кластеров Apache Kafka®;
* просматривать информацию о [квотах](../../managed-kafka/concepts/limits.md#mkf-quotas) сервиса Managed Service for Apache Kafka®;
* просматривать информацию об операциях с ресурсами сервиса Managed Service for Apache Kafka®.

Включает разрешения, предоставляемые ролью `managed-kafka.editor`.

Для создания кластеров Apache Kafka® дополнительно необходима роль `vpc.user`.