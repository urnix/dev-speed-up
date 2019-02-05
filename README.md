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
  * We can save case
  * We can use regexps
* Добавление папок в игнор индексации
#### Edit code and Refactoring
* Move anything: F6
* Rename anything: Shift + F6 
  * We can rename mentioning and comments automatically or not 
* Extract variable/constant: Alt + Cmd + V 
* Inline variable/constant: Alt + Cmd + N 
* Duplicate line or selection: Cmd + D
* Change Case: Shift + Cmd + U
* Свернуть/развернуть
* Комментарри одно/многострочные, жс док
* Перемещение по словам и в начало конец строки (мак)
* Suggestions to fix/change anything (лампочка)
  * Alt + Enter (E.g. замена тернарного оператора на if)
* Surround by code: Alt + Cmd + T
  * Use Emmet in html
* Перемещение строк вверх/вниз
* Paste from clipboard history: Shift + Cmd + V
* Live templates
  * E.g. вывод лога
* Multiple selection
  * Зажимаем Alt и растягиваем выделение на несколько строк
  * Зажимаем Alt и кликаем - каждый клик добавляет выделение 
* Emmet (more here https://en.wikipedia.org/wiki/Emmet_(software))
* Saving snippets
### Work with Git
* History
* History of file
* Annotations
* Hotkeys for remote: pull, fetch, push
* Local History
* Comparing of branches
* Comparing of files (from different branches or from one)
* Merge and conflicts
* Displaying uncommitted files
### Code inspections
* Dictionaries
* Игноры идея/тслинт
### Formatting
* Загрузка кастомного форматирования
* Clearing unused imports: Ctrl + Alt + O (Or using formatting: Cmd + Alt + L)
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
