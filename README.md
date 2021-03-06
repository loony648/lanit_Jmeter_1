## Test plan for Trello API on Jmeter
### Использованные ресурсы:

[Trello API](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/)

[JMeter for Arch Linux](https://aur.archlinux.org/packages/jmeter/)

[JMeter official download page](https://jmeter.apache.org/download_jmeter.cgi)

### Описание каждой "катушки"

setUp - проверка соединения с Trello

tearDown - архивирование всех карточек со всех листов

UC-1 создание карточки

UC-2 перемещение карточки во второй лист

UC-3 добавить описание к карточке

UC-4 переместить карточку в третий лист

UC-5 удаление 

