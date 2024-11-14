# LR6
# Лабораторная работа №6 "Система контроля версий"
## Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git API, опыт работы с локальным и удаленным репозиторием.
## Ход работы
### 1. Создание аккаунта на GitHub
[Скриншот регистрации](screenshots/1.png)
### 2. Fork репозитория
[Скриншот Fork](screenshots/2.png)
### 3. Установка Git
[Скриншот установки](screenshots/3.png)
### 4. Настройка Git
[Скриншот настройки](screenshots/4.png)
```bash
git config --global user.name "4315 Влад Юдин"
git config --global user.email "vladislav.yudin.200@gmail.com"
```
### 5. Клонирование репозитория
[Скриншот клонирования репозитория](screenshots/5.png)
```bash
git clone git@github.com:devaq454/LR6.git
```
### 6. Добавление файла через GitHub и подтягивание изменений
[Скриншот добавления файла](screenshots/6.png)
```bash
git pull origin master
```
### 7. Получение истории операций
[Скриншот истории операций](screenshots/7.png)
```bash
git log master
```
### 8. Просмотр последних изменений
[Скриншот последних изменений](screenshots/8.png)
```bash
git show
```
### 9. Слияние веток и разрешение конфликта
[Скриншот слияния веток](screenshots/9.png)
```bash
git merge second
```
### 10. Удаление ветки
[Скриншот удаления ветки](screenshots/10.png)
```bash
git branch -d second
```
### 11. Фиксация изменений
[Скриншот фиксации изменений](screenshots/11.png)
```bash
git add *.cpp *.go
git commit -m "created cpp and go files"
```
### 12. Откат коммита
[Скриншот отката](screenshots/12.png)
```bash
git reset --hard HEAD~1
```
### 13. Создание ветки для отчёта
[Скриншот создания ветки "отчет"](screenshots/13.png)
```bash
git checkout -b отчет
```

### 14. Оформление отчёта
Создание файла `README.md` и его заполнение.
[Скриншот создания и добавление папки screenshots](screenshots/14.png)

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

### 15. История операций
При помощи команды "git log --pretty=format:"%h - %ad - %an: %s" --date=short" получим следующую информацию в укороченном виде:
```
26902fa - 2024-11-14 - 4315 Влад Юдин: created README and screenshots for отчет
9e95cba - 2024-11-14 - 4315 Влад Юдин: add screenshots 1-13
b829aef - 2024-11-14 - 4315 Влад Юдин: file for go has been created!
5e87a60 - 2024-11-14 - 4315 Влад Юдин: created 3 more cpp files
1507162 - 2024-11-14 - 4315 Влад Юдин: created second cpp file
ffb986d - 2024-11-14 - 4315 Влад Юдин: created first cpp file
02d6c5f - 2024-11-15 - devaq454: Create newfile.txt
921f53b - 2020-11-21 - Kurtyanik: Обновление информации
c08a654 - 2020-11-21 - Kurtyanik: Файл создан пустым
3c6e913 - 2020-11-21 - Kurtyanik: Initial commit
```
