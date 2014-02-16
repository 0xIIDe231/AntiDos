antidos
=========

Легкая защита от частых запросов к PHP сайту.

Защита предназначена прежде всего для сайтов размещенных на виртуальном хостинге с лимитом процессорного времени.

Особенности:
 - Исключение роботов поисковых систем из обработки с помощью обратных DNS-запросов.
 - Сам скрипт загружает процессор по минимуму за счет перераспределения нагрузки на дисковую систему.
 - Скрипт подключается в главных файлах сайта через которые проходят все запросы (например общедоступные и административные части).
 - Срипт не загрязняет пространство имен, т.к. создается одна переменная-функция в конце кода сайта.

