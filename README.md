# RuTracker — источник загрузок Hydra

Добавьте эту прямую ссылку в список источников загрузок Hydra:

```text
https://raw.githubusercontent.com/gdetotut1/hydra-rutracker-feed/main/data/rutracker.json
```

Каталог находится в [`data/rutracker.json`](data/rutracker.json). Верхний уровень JSON содержит `name` и `downloads`. Каждая раздача содержит `title`, `uris`, `uploadDate` и `fileSize`; ссылки в `uris` имеют формат magnet.

Фид формируется локально после успешного завершения сбора и применения отбора тем. Обновления публикуются по тому же адресу.

Названия приведены к формату `Game Name [v 1.2 + DLC] (2026) PC | Portable`: имя игры стоит первым, служебные метки RuTracker и языковые блоки удалены. Версии, дополнения, издания и тип сборки сохраняются. После обновления JSON источник требуется синхронизировать в Hydra и дождаться обработки.
