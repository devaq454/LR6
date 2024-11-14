# LR6
# Лабораторная работа №6 "Система контроля версий"
## Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git API, опыт работы с локальным и удаленным репозиторием.
## Ход работы
### 1. Создание аккаунта на GitHub
[Скриншот регистрации](screenshots/1.jpg)
### 2. Fork репозитория
[Скриншот Fork](screenshots/2.jpg)
### 3. Установка Git
[Скриншот установки](screenshots/3.jpg)
### 4. Настройка Git
[Скриншот настройки](screenshots/4.jpg)
```bash
git config --global user.name "4315 Влад Юдин"
git config --global user.email "vladislav.yudin.200@gmail.com"
```
### 5. Клонирование репозитория
[Скриншот клонирования репозитория](screenshots/5.jpg)
```bash
git clone git@github.com:devaq454/LR6.git
```
### 6. Добавление файла через GitHub и подтягивание изменений
[Скриншот добавления файла](screenshots/6.jpg)
```bash
git pull origin master
```
### 7. Получение истории операций
[Скриншот истории операций](screenshots/7.jpg)
```bash
git log master
```
### 8. Просмотр последних изменений
[Скриншот последних изменений](screenshots/8.jpg)
```bash
git show
```
### 9. Слияние веток и разрешение конфликта
[Скриншот слияния веток](screenshots/9.jpg)
```bash
git merge second
```
### 10. Удаление ветки
[Скриншот удаления ветки](screenshots/10.jpg)
```bash
git branch -d second
```
### 11. Фиксация изменений
[Скриншот фиксации изменений](screenshots/11.jpg)
```bash
git add *.cpp *.go
git commit -m "created cpp and go files"
```
### 12. Откат коммита
[Скриншот отката](screenshots/12.jpg)
```bash
git reset --hard HEAD~1
```
### 13. Создание ветки для отчёта
[Скриншот создания ветки "отчет"](screenshots/13.jpg)
```bash
git checkout -b отчет
```

### 14. Оформление отчёта
Создание файла `README.md` и его заполнение.
[Скриншот создания и добавление папки screenshots](screenshots/14.jpg)

# Логи команд

В процессе выполнения лабораторной работы были использованы следующие команды:

```
git config --global user.name
git config --global user.email
git clone
git pull
git log
git checkout
git merge
git status
git add .
git commit -m ""
git push origin --delete
git branch
git reset
```
