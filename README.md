 **Instructions for GIT's commmands**

# 1. After setup GIT and Visual Studio Code 

## (Действия после установки GIT и Visual Studio Code)
*********************************
+ Open the programm Visual Studio Code
(Откройте программу Visual Studio Code)**

+ Open folder for repozitory (Откройте каталог с репозиторием)

    *__Menu => File => Open Folder..__*

+ Open window for command line (Запустите окно с командной строкой)

    *__Menu => View => Terminal..__*

+ Make sure the correct setup,
enter the command (Убедитесь в корректной установке GIT)

    **_git --version_**

+ Initilize yourself for GIT, enter commands (Инициализируйтесь в GIT)

     **_git config --global user.name "your_name"_**
     
     **_git config --global user.mail "your_mail@ya.ru"_**

+ Check your initialization,
enter commands (Убедитесь, что ваша инициализация в GIT прошла успешно)

    **_git config --global user.name_**
    
    **_git config --global user.mail_**
****************************
# 2. Initilize of repository

## (Инициализация репозитория)
****

* enter the command (Введите команду)

    **_git init_**

* check that message is correct (Убедитесь в инициализации по сообщению)

    **_Intilized empty Git repozitory in E:\ ..._**

# 3. Creating of new file 
## (Создание нового файла)
*******

* Open the menu (Откройте меню)

    **Menu => File => New File**

* Enter the file name (.md) (Введите имя файла с расшширением .md)

* Add change to the repository, enter commands (Добавьте изменения в репозиторий с помощью следующих команд)

    **_git add file_name_**
    
    **_git commit --m "message"_**

* Check, that message is correct (Проконтролируйте что нет сообщений об ошибке)

## _This procedure to repeat after every significant change!_

# 4. Viewing of versions, branch and moving between them

## (Просмотр существующих версий и перемещение между ними)

* **_git log_** - command
 outputs log of saves (Выводит журнал всех сохраненных версий)

* **_git checkout num_version (branch)_** - allow to move between versions (Позволяет перемещаться между версиями и ветками)

* **_git checkout master (branch_name)_** - set actual version (Активирует указанную версию или ветку)

* **_git  status_** - show on which branch we now (Показывает состояние файла текущей версии или ветки)

* **_git  diff_** - show difference between saved file and current changes (Показывает внесенные и несохраненные измененния файла)

* **_git  merge branch_name_** - merge a branch with master_branch (Сливает второстепенную ветку с основной)

# 5. Work with repozitory 

* Command **_Fork_** - create copy of outside repozitry folder on your repozitory (создает копию каталога с внешнего репозитория в вашем реопзитории)

* Command **_Clone_** - copy repozitory folder on your local folder (Копирует каталог с внешнего Вашего репозитория в локальный каталог)

* Command **_Pull_** - pull changes from your repozitory on lokal folder (Стягивает изменения с внешнего репозитория на локальныйю При этом пытается слить ветки)

* Command **_Push_** - push changes from your lokal folder on repozitory (Проталкивает изменения с локального каталога на внешний репозиторий)


* Button **_Compare & pull request_** - allow to suuggest changes for another repozitory (Позволяет предложить изменения в файл чужого репозитория)