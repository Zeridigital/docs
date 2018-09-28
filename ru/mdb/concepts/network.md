# Сеть и кластеры БД

При создании кластера вы можете:

- задать сеть для самого кластера;
- задать подсети для каждого из хостов кластера;
- запросить публичный IP-адрес для доступа к кластеру извне Облака.

Вы можете создать кластер, не задавая подсети для хостов, если выбранная для каждого хоста зона доступности содержит ровно одну подсеть сети кластера.

## Имя хоста и FQDN {#hostname}

Имя для каждого хоста в кластере [!KEYREF mdb-short-name] генерирует при его создании. Это имя будет являться доменным именем хоста (FQDN).

FQDN можно использовать для доступа к хосту в рамках одной облачной подсети. Подробнее читайте в [документации сервиса Yandex [!KEYREF vpc-short-name]](../../vpc/).

Имя хоста и, соответственно, FQDN невозможно изменить — чтобы получить хост БД с другим именем, удалите старый хост из кластера и создайте новый.

## Публичный IP-адрес хоста

Любой хост в кластере может быть доступен извне Яндекс.Облака по публичному IP-адресу. Запросить публичный адрес можно только при создании хоста — чтобы получить хост, доступный из интернета, добавьте новый хост в кластер.

При удалении хоста назначенный публичный IP-адрес отзывается.