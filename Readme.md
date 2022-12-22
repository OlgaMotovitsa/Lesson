# Инструкция по работе с Git

## Что такое гит?
***Git*** - это самая популярная реализация распределенной системы контроля версий (версионность поддерживается и на сервере и у каждого клиетна). Самой распространенной реализации ***Git*** является (GitHub)[https://github.com]

## Позготовка репозитория
Для создания репозитория используется команда git init. Для этого необходимо открыть в терминале папку с будущим репозиторием и написать git init

### Добавление файлов к коммиту
Для добавления файла к новому коммиту используется команда *git add*. Используется она след. образом: в терминале с папкой-репозиторием пишем *git add название файла*.

### Создание коммита
Для создания новой фиксации коммита используется команда git commit. Для этого в терминале с папкой репозиторием пишем git commit -m "Сообщение к коммиту писать ***обязательно!!!"***

## Журнал изменений
Для просмотра истории изменений используется команда git log. Для это в терминале с папкой-репозиторием необходимо написать git log

## Перемещение между коммитами
Для перемещения на другую фиксацию (коммит) используется команда checkout. Для этого необходимо как показано в предыдущем пункте, в журнале изменений найти необходимый коммит и его хеш(номер), после чего в терминале с папкой-репозиторием надо написать *git chechout*<хеш коммита>*. После выполнения этой команды мы попадаем в состояние **detached head**, в котором никакие следующие коммиты сохраняться не будут. Для выхода из этого состояния нещбходимо писать git chechout master

## Ветки в гит
Ветка – это последовательность коммитов, так называемый черновик. Чтобы создать ветку нужно ввести в терминале с папкой-репозиторием команду git branch имя ветки. Для переключения на ветку нужно ввести в терминале с папкой-репозиторием команду git checkout имя ветки. Также команда git branch отобразит список существующих веток и отметит звездочкой актуальную ветку.

## Слияние веток и разрешение конфликтов

## Удаление веточек

## Другие команды Git
