## Установка
### * Linux

** Installation GIT **
```console
sudo apt update 
sudo apt upgrade
sudo apt install git 
```
** Installation GIT-interface *
```console
sudo apt install git-gui qgit
sudo apt install git-doc
```
** Check **
```console
git --version
```

### * Windows
Скачать установщик и следовать инструкциям по установки

## Создание пользователя
```console
$ git config --global user.name "John Doe"
$ git config --global user.email "johndoe@example.com"
```

## Настройка ветки по умолчанию
Когда вы инициализируете репозиторий командой `git init`, Git создаёт ветку с именем _master_ по умолчанию. Начиная с версии 2.28, вы можете задать другое имя для создания ветки по умолчанию.

Например, чтобы установить имя _main_ для вашей ветки по умолчанию, выполните следующую команду:
```console
$ git config --global init.defaultBranch main
```

## Проверка настроек
Если вы хотите проверить используемую конфигурацию, можете использовать команду:
```console
git config --list
```

## Инициализация
```console
git init  
git add
```

## Первый коммит
```console
git commit -m "Init"`
```

## Добавление изменения на github
