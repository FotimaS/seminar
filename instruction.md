# Инструкция по работе с GIT

# Базовые команды

*git init* – **инициализация локального репозитория**

*git status* – **получить информацию от git о его текущем состоянии**

*git add* – **добавить файл или файлы к следующему коммиту**

*git commit -m “message”* – **создание коммита.**

*git log* – **вывод на экран истории всех коммитов с их хеш-кодами**
## Команды для ветвления

*git branch* - **команда для вывода всех веток на экран**

*git branch <branch_name>* - **создание новой ветки**

*git checkout <branch_name>* - **переход на другую ветку**

*git merge <branch_name>* - **слияние веток между собой**

*git branch -d <branch_name>* - **удаление уже слитой ветки**

*git log --graph* - **вывод журнала изменений с визуализацией**


## Команда для удаленного репозитория 

*git clone* - **клонирование удаленного репо на локальный компьютер**

*git push* - **отправка изменений с локального компьютера на удаленный репо**

 *git pull* - **стягивание изменений с  удаленный репо на локальный компьютер и их применения**