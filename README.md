Разработать одностраничное приложение на React: текстовый редактор заметок с тегами. (Front-end) 

Действия: 
1. Создание, редактирование, просмотр и удаление заметок; 
2. Фильтр заметок по тегу; 
3. Добавление и удаление тегов из списка. 
4. Данные хранить в json формате. 
5. Использование CSS препроцессора. 
6. Использование TypeScript 


Примечания: 
Во время редактирования заметки пользователь может создавать теги, используя символ #. 
Пользователь вводит текст “I wanna go to #shop”. 
По мере (окончании) ввода должен создаться соответствующий тег и отобразиться в списке под текстовым полем. 
При редактировании заметки все слова, соответствующие тегам, должны подсвечиваться.

Команды:

npm start

Запуск проекта. Осуществляется с помощью команды start

[Эта команда запускает приложение в режиме разработки. В результате запускается сервер и открывается браузер с адресом http://localhost:3000, в котором показывается рабочее React-приложение.]


npm test

Запуск тестов

npm run build

Сборка приложения

[Эту команду обычно запускают после завершения разработки проекта. Она выполняет сборку приложения из исходных файлов для продакшена. Полученные оптимизированные файлы помещаются в папку build и они отвечают за функционал всего приложения. После сборки вы можете приступать к развертыванию приложения.]

npm run eject

Команда, которая позволяет извлечь все файлы конфигурации и зависимости непосредственно в проект. 

[Эту команду можно ввести только один раз. После этого поддержание всей этой конфигурации и сценариев вы выполняете самостоятельно. Обычно это используется, когда вы хотите настроить конфигурацию проекта так как вам это нужно.]
