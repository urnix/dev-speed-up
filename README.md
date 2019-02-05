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

## WebStorm Tops

### Navigation 
#### By App
		* Переход в инспекторы и панели: Alt + F1
		* Переход между вкладками: Shift + Cmd + [, Shift + Cmd + ]
#### By Files
	* Последние файлы: Cmd + E
    * Последние измененнные файлы: Shift + Cmd + E
	* Pабота с закладками - Список: Cmd + 2 / Cmd + F3, Добавление: F3
	* Поиск по всему: Double Shift
    * Поиск по файлам: Shift + Cmd + O
  	* Поиск по большим буквам (работает во всех панелях)
	* По папкам: `/`
#### By Code
	* По ошибкам: F2 / Shift + F2
    * Переход/Декларация: Cmd + B
	* К строке: Cmd + L
	* Cмотреть сигнатуру/справку: F1 / Cmd + P
	* Вперед/назад: Alt + Cmd + Arrows
	* К последним изменениям: Shift + Cmd + Backspace
### Search
	* Поиск множества позиций в файле
	* Поиск в окне поиска / в панели поиска: Enter / Cmd + Enter
	* Aвтозамена 
		C cохранениеv регистра
		C регекспами
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
	* Oкружение кодом: Alt + Cmd + T
	* Перемещение строк вверх/вниз
	* Emmet
	* Мульти буфер
	* Живые шаблоны
		вывод лога
	* Блочное выделение
		Растягивание выделения с альт
		Клики с альт
	* Вставка из мультибуфера
	* Хранение сниппетов
### Work with Git
	* Хистори
	* Хитстори файла
	* Аннотации
	* Хоткеи на ремот: пулл, фетч, пуш
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
	* Экспорт/импорт настроек
	* Внешний вид
		Отключение вкладок
		Отключение навигации
		Цветовые схемы и контрастность
	* Горячие клавиши
	* Длина строки и таб сайз
	* Форматирование
	* Спилинг
		Ручной импорт словарей
			/USERNAME/.WebStorm2018.3/config/options/cachedDictionary.xml
	* Плагины
	* Привязка гита, преттиер, тс, фреймворки - вкладка нод
	* Список игнореных папок
	* Show parameter name hint - off
	* Производительность
		-Xmx3072m
		memory indicator
	* Maximum line number in clibpoard
