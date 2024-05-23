# PD6
Здесь представлены результаты курсовой работы про проектной деятельности в 6 семестре.

Структура:
- В папке pipelines располагаются yml файлы, которые используются для настройки пайплайнов
- В папке form находится файл со скриптом, который используется в гугл форме

Ссылка на форму:
https://docs.google.com/forms/d/e/1FAIpQLScrQ1_q1IXwbjKYW9I1vIOGuSUpvJuLM9PFrZ7VpRAvVnrpMg/viewform?usp=sf_link

Ссылка на таблицу:
https://docs.google.com/spreadsheets/d/1Nkq8vOhzg-HbW5NefhoUxLq1zpCberF9O4tKmtBArR0/edit?usp=sharing

Настройка пайплайна:
Расположите файл linelint.yml в корневой директории. Создайте папку .github, далее в ней создайте папку workflows и поместите туда файл dotnet.yml

Защита ветки:
Перейдите в Settings -> Branches -> Add branch protection rules. В Branch name pattern укажите main. Затем установите галочку в поле Lock branch.

Передача прав на репозиторий:
Перейдите в Settings, пролистайте вниз до группы Danger zone, перейдите в Transfer ownership. В New owner выберите Specify an organization or username и в появившемся поле введите username преподавателя. Далее по указанной инструкции в конце страницы укажите название вашего репозитория и нажмите I understand, transfer thir repository
