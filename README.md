# Dark and Crafter — сборка модов

Отсюда лаунчер Dark and Crafter берёт моды для игры.

* `manifest.json` — список файлов сборки с SHA-1 и размером. Лаунчер сверяет его с папкой игры,
  докачивает только изменившееся и удаляет то, что из сборки убрали. Моды, которые игрок положил сам, не трогаются.
* `mods/` — моды Dark and Crafter и Fabric API (Fabric API распространяется по лицензии Apache-2.0).

`manifest.json` руками не правится — он генерируется заново при каждом обновлении
(`make-pack.bat` из папки лаунчера или автоматически при сборке модов).

Адрес сборки в лаунчере (зашит по умолчанию):
`https://raw.githubusercontent.com/mezershow1337/DarkAndCrafter-Pack/main/manifest.json`
