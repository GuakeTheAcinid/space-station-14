<p align="center"> <img alt="Space Station 14" width="880" height="300" src="https://raw.githubusercontent.com/space-wizards/asset-dump/de329a7898bb716b9d5ba9a0cd07f38e61f1ed05/github-logo.svg" /></p>

Space Station 14 это ремейк SS13, который работает на собственном движке [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), написанном на C#.

Это репозиторий форка Space Station 14 от Workbench Team который используется на нашем основном сервере Космическая станция им. Aru Moon, и его также можете использовать и вы для получения эксклюзивных фишек форка. Если вам нужен только русский перевод для игры без наших фишек, перейдите в [master-ru ветку](https://git.arumoon.ru/Workbench-Team/space-station-14/-/tree/master-ru).

Вы можете использовать эту ветку как для создания собственного сервера, так и для контрибьюта в работу нашего сервера.

## Ссылки

[Сайт игры](https://spacestation14.io/) | [Workbench Discord](https://discord.com/servers/workbench-team-727015266642296924) | [Workbench Revolt](https://rvlt.gg/wcYASVKF) | [Steam игры](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Скачать лаунчер](https://spacestation14.io/about/nightlies/)

## Документация

На официальном сайте с [документацией](https://docs.spacestation14.io/) имеется вся необходимая информация о контенте SS14, движке, дизайне игры и многом другом. Также имеется много информации для начинающих разработчиков.

## Вклад

Если вы хотите предложить добавление нового контента или редактирование существующего, мы с радостью ждём ваши изменения на нашем [основном репозитории GitLab](https://git.arumoon.ru/Workbench-Team/space-station-14/-/tree/arumoon-server) (рекомендуется) или [зеркале GitHub](https://github.com/Workbench-Team/space-station-14/tree/arumoon-server). Если вам нужна помощь, посмотрите текущие [обсуждения в GitLab](https://git.arumoon.ru/Workbench-Team/space-station-14/-/issues) или лучше перейдите на Discord или Revolt сервер Workbench Team для более удобной коммуникации.

## Готовая сборка

Статус сборки: [![pipeline status](https://git.arumoon.ru/Workbench-Team/space-station-14/badges/master-ru/pipeline.svg)](https://git.arumoon.ru/Workbench-Team/space-station-14/-/commits/master-ru)

Готовые билды сборки вы можете скачать из [CDN хостинга (быстро)](https://ss14.arumoon.ru/builds/master-ru-builds.html) или [артефактов CI/CD (медленно)](https://git.arumoon.ru/Workbench-Team/space-station-14/-/pipelines?page=1&scope=all&ref=master-ru&status=success)

## Самостоятельная сборка

1. Склонируйте этот репозиторий.
2. Переключитесь на ветку arumoon-server
3. Запустите скрипт `RUN_THIS.py` для инициализации субмодулей и скачивания движка.
4. Соберите решение через Visual Studio или dotnet в терминале.

[Более детальная инструкция для сборки.](https://docs.spacestation14.io/getting-started/dev-setup)

## Лицензия

Весь код репозитория лицензирован под [MIT](https://git.arumoon.ru/Workbench-Team/space-station-14/blob/master-ru/LICENSE.TXT).

Большинство ассетов лицензированы под [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) если не имеют иное. Ассеты имеют свою лицензию и авторские права в файле метаданных. [Пример](https://git.arumoon.ru/Workbench-Team/space-station-14/blob/master-ru/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Обратите внимание, что некоторые ассеты лицензированы на некоммерческой основе [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) или аналогичной некоммерческой лицензией, и их необходимо удалить, если вы хотите использовать этот проект в коммерческих целях.
