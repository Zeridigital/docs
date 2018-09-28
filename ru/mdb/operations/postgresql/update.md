# Изменение настроек кластера и базы данных

После создания кластера вы можете изменить:

- Имя пользователя — владельца БД.
- Список пользователей базы данных (подробнее об управлении пользователями в разделе [[!TITLE]](cluster-users.md)).
    > [!NOTE]
    > 
    > [!KEYREF mdb-short-name] резервирует 15 соединений для служебных пользователей для каждой базы данных [!KEYREF PG]. Учитывайте это, планируя количество пользователей БД. Например, при настройке `"max_connections": 100` для ваших пользователей должно быть зарезервировано не больше 85 соединений.
- Включенные для базы данных расширения [!KEYREF PG] (подробнее об управлении расширениями в разделе [[!TITLE]](cluster-extensions.md)).
- Любые настройки сервера [!KEYREF PG], описанные в [документации СУБД](https://www.postgresql.org/docs/10/static/runtime-config.html).
- Режим работы менеджера соединений (PgBouncer).

---

**[!TAB Консоль управления]**

Чтобы просмотреть или изменить настройки кластера перейдите на страницу каталога и нажмите плитку **Yandex Managed Databases**. Затем нажмите на имя нужного кластера.
Вы можете:

- Управлять пользователями на вкладке **Пользователи**. Чтобы удалить имеющегося пользователя или изменить пароль — нажмите значок ![](../../../_assets/vertical-ellipsis.svg) в строке таблицы.
- Создавать новые резервные копии на вкладке **Резервные копии**.
    
---
