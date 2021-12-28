# DoubleDox-Racer

Hello. Here is my Racing game.
It's not actually a full game.. It's like an racing game engine.
You can provide resources from some old games to it, and "play" these games with this engine.
Everything is in development state and can contain bugs

How to add game to engine:
- Ensure that DD Racer is not running
- Open DD Racer root folder
- Open "Resources" folder (or create and open, if not exists)
- Open "games.ini" file (or create and open, if not exists)
- Add line in format <KEY>=<PATH>, where KEY is game id (see at the bottom of this doc), and PATH is resources location
- Save and close file
- Run DD Racer

Привет. Это моя гоночная игра.
Точнее, это не совсем полноценная игра.. Это скорее движок гоночной игры.
Вы можете предоставить ресурсы от некоторых старых игр, и "играть" в них через этот движок.
Всё находится в стадии разработки и может содержать баги.

Как добавить игру в движок:
- Убедитесь, что DD Racer не запущен
- Откройте корневую папку DD Racer
- Откройте папку "Resources" (или создайте и откройте, если не существует)
- Откройте файл "games.ini" (или создайте и откройте, если не существует)
- Добавьте строку в формате <KEY>=<PATH>, где KEY это идентификатор игры (см. в конце), и PATH это путь к ресурсам игры
- Сохраните и закройте файл
- Запустите DD Racer
  
Games support (Поддержка игр)

|Game|ID|Tracks|Cars|Comments|
|----|--|------|----|--------|
|NFS 1|nfs1|Almost done| | |
|NFS 2|nfs2|Almost done|Almost done||
|NFS 3|nfs3|Almost done|Almost done||
|NFS 4|nfs4|Almost done|Almost done||
|NFS 5|nfs5|In progress|In progress||
|Carmageddon 1|carma1|In progress|Almost done|!Decryption needed!|
|Carmageddon 2|carma2| |In progress||

Initially carmageddon 1 resources are encrypted (And cannot be parsed by engine). To decrypt files:
- Run the Carmageddon 1 game
- Type IWANTTOFIDDLE (case-sensitive) at the car selection screen. 
- Close the game. Now the external data files, which are in text format, will be decrypted to allow parsing.

Examples of games.ini content (Примеры содержимого games.ini)\
\
carma1=D:\Games\SteamLibrary\steamapps\common\Carmageddon1\
carma2=D:\Games\SteamLibrary\steamapps\common\Carmageddon2\
nfs1=D:\Games\NFS\nfs\
nfs2=D:\Games\NFS\nfs2se
  
