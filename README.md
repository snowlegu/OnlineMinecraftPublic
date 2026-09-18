# OnlineMinecraft Public Downloads

Готовые клиентские сборки мода OnlineMinecraft для добровольного учёта игровых сессий в панели Yamazaki Syndicate.

## Скачать

- [Minecraft 1.16.5](https://github.com/snowlegu/OnlineMinecraftPublic/raw/main/OnlineMinecraft-1.16.5-0.2.0.jar)
- [Minecraft 1.20.1](https://github.com/snowlegu/OnlineMinecraftPublic/raw/main/OnlineMinecraft-0.2.0.jar)
- [Minecraft 1.21.4](https://github.com/snowlegu/OnlineMinecraftPublic/raw/main/OnlineMinecraft-1.21.4-0.3.0.jar)

Выберите только одну сборку под свою версию Minecraft и положите `.jar` в папку `.minecraft/mods`.
Для версии 1.21.4 нужен Java 21, Fabric Loader 1.21.4 и Fabric API для 1.21.4.

## Настройка

1. Запустите Minecraft с модом один раз.
2. В Discord на сервере Yamazaki выполните `/minecraft_link`.
3. В игре нажмите `O` — откроется меню OnlineMinecraft.
4. Вставьте полученный токен обычным `Ctrl+V` и нажмите «Сохранить».
5. Зайдите на Minecraft-сервер — активность начнёт отправляться автоматически.

Настройки также сохраняются в `config/online_minecraft.json`.

Без личного токена мод ничего не отправляет. Мод передаёт только игровые события сессии, ник, сервер и время активности. Он не читает файлы компьютера, пароли, Discord, буфер обмена или содержимое чата.

Исходный код находится в репозитории [OnlineMinecraft](https://github.com/snowlegu/OnlineMinecraft), а этот репозиторий содержит готовые бинарные сборки для скачивания.

Проверить целостность файлов можно по [SHA256SUMS.txt](https://github.com/snowlegu/OnlineMinecraftPublic/raw/main/SHA256SUMS.txt).
