# OnlineMinecraft Public Downloads

Готовые клиентские сборки мода OnlineMinecraft для добровольного учёта игровых сессий в панели Yamazaki Syndicate.

## Скачать

- [Minecraft 1.16.5](https://github.com/snowlegu/OnlineMinecraftPublic/raw/main/OnlineMinecraft-1.16.5-0.1.0.jar)
- [Minecraft 1.20.1](https://github.com/snowlegu/OnlineMinecraftPublic/raw/main/OnlineMinecraft-0.1.0.jar)

Выберите только одну сборку под свою версию Minecraft. Положите `.jar` в папку `.minecraft/mods`.

Для работы нужны соответствующие **Fabric Loader** и **Fabric API**.

## Настройка

1. Запустите Minecraft с модом один раз.
2. В Discord на сервере Yamazaki выполните `/minecraft_link`.
3. Вставьте полученный токен в `config/online_minecraft.json` в поле `pairingToken`.
4. Перезапустите игру и зайдите на сервер.

Без личного токена мод ничего не отправляет. Мод передаёт только игровые события сессии, ник, сервер и время активности. Он не читает файлы компьютера, пароли, Discord, буфер обмена или содержимое чата.

Исходный код хранится в приватном репозитории проекта. Этот репозиторий содержит только готовые бинарные сборки для скачивания.

Проверить целостность файлов можно по [SHA256SUMS.txt](https://github.com/snowlegu/OnlineMinecraftPublic/raw/main/SHA256SUMS.txt).
