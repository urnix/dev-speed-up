# Dev Speed Up
Tips to speed up development in JetBrains WebStorm and not only

## Highly Recommended Software 
  
* Homebrew 
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
* NVM (npm v6.11.5 for firebase functions, npm v8.9.0 for all the rest)
```
brew update
export NVM_DIR="$HOME/.nvm"
. "$(brew --prefix nvm)/nvm.sh"
```
* YARN
```
brew install yarn
```
* ITerm 2
```
brew cask install iterm2
```
* oh-my-zsh (killer-feature - fast search for recent commands)
```
brew install zsh zsh-completions
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
* Screen layout app (e.g. Spectacle App)
* JetBrains IntelliJ IDEA or WebStorm

## WebStorm Tips

### Navigation 
#### By App
	
* Switching between panels: Alt + F1
* Switching between tabs: Shift + Cmd + [, Shift + Cmd + ]
#### By Files
* Recent files: Cmd + E
  * Recent edited files: Shift + Cmd + E
* Work with bookmarks:
  * List: Cmd + 2 / Cmd + F3
  * Add: F3
  * Also personal hotkey can be assigned 
* Search for everything: Double Shift
  * Search by files: Shift + Cmd + O
  * Can be found by first letters in file name or path
  * Can be found using `/` for specify folders in path
  * Type `/` in the end to find folder
#### By Code
* To next error: F2 / Shift + F2
* To declaration: Cmd + B
* To line: Cmd + L
* Show JSDoc: F1
* Show signature parameters: Cmd + P
* Go/Back through history: Alt + Cmd + Arrows
* To last changes: Shift + Cmd + Backspace
### Search
* We can select all found substrings: Shift + Cmd + G 
* Open results of search in Search Panel: Cmd + Enter
* Replace all
  * We can save shift
  * We can use regexpr
* Добавление папок в игнор индексации
#### Edit code and Refactoring
* Перенос и переименование (с изменением смежных)
* Вынесение/инлайн переменной
* Дублирование
* Изменение регистрв
* Свернуть/развернуть
* Комментарри одно/многострочные, жс док
* Перемещение по словам и в начало конец строки (мак)
* Предложение исправления (лампочка)
  * Alt + Enter (E.g. замена тернарного оператора на if)
* Окружение кодом: Alt + Cmd + T
* Перемещение строк вверх/вниз
* Emmet
* Мульти буфер
* Живые шаблоны
  * E.g. вывод лога
* Блочное выделение
  * Зажимаем Alt и растягиваем выделение на несколько строк
  * Зажимаем Alt и кликаем - каждый клик добавляет выделение
* Вставка из множественного 
* Хранение сниппетов
### Work with Git
* Хистори
* Хитстори файла
* Annotations
* Hotkeys for remote: pull, fetch, push
* Работа с локалхистори
* Сравение веток
* Сравнение файлов
* Мерж и конфликты
* Просмотр незакоммиченных
### Code inspections
* Словари
* Игноры идея/тслинт
### Formatting
* Загрузка кастомного форматирования
* Организация импортов
* Таб 2 спейса
### Settings
* Программа раннего доступа
* Список хоткеев и настройка хоткеев
* Export/Import settings
* Appearance
  * Tabs - turn off
  * Navigation - turn off
  * Color schemes and contrasts
* Hotkeys settings
* Line length, tabs size
* Форматирование
* Spelling
  * Ручной импорт словарей
    /USERNAME/.WebStorm2018.3/config/options/cachedDictionary.xml
* Plugins
* Bind apps: git, Prettier, TypeScript, Frameworks - Node tab
* Excluded directories list Список игнореных папок
* `Show parameter name hint` - turn off
* Performance
  * -Xmx3072m
  * memory indicator
* Maximum line number in clipboard
