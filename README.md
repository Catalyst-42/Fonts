# Fonts

Этот репозиторий хранит исходники шрифта Metafont и шрифта из Aseprite.  
JSON и png файлы можно использовать на сайте (https://yal.cc/r/20/pixelfont/) для генераций шрифта из изображений  

# Замена шрифта в приложении Aseprite
Если вы хотите установить расширенный шрифт для приложения Aseprite, переместите в папку шрифтов измененное изображение aseprite_font.png
Папка шрифтов Aseprite может быть найдена через 

`Steam` > `Aseprite` > `ПКМ` > `Управление` > `Просмотреть локальные файлы` > `data` > `fonts`  
  
Или через само приложение Aseprite  
  
`Preferences` > `Theme` > `Open Folder` > `Поднимаетесь на 3 уровня выше` > `fonts`  

На всякий случай сохраните отдельно исходный png файл шрифта 
После замены изображения откройте снова Aseprite чтобы применить шрифты. 

Если вы хотите расширить / изменить готовое изображение шрифта, соблюдайте несколько правил.
1. Размер глифа не может быть больше чем 8x8 пикселей
2. Используйте сетку `0 -2 11 11`
3. Прозрачне пиксели используются для увеличения ширины глифа (в противном случае символы будут липнуть друг к другу)
4. Для пустых символов оставьте изображение полого квадратика
5. Добавление новых рядов следует делать блоками по 16 в высоту
6. Соотнести символы можно по таблице Unicode (https://unicode-table.com/ru/)

# Ase.ttf
Этот шрифт был построен на основе исходного спрайта шрифта из Aseprite.

# MetaFont
Шрифт, основанный на cp437 IBM BIOS +, только этот шрифт был сделан так, чтобы каждый глиф был именно квадратным. 
