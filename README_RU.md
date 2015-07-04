# FontAwesomeGetChar
Простой JavaScript скрипт для получения юникод символа иконки шрифта Awesome по ее имени.

## Установка
Скачайте шрифт Awesome с http://fortawesome.github.io/Font-Awesome/ и скопируйте файл "fontawesome-webfont.ttf" 
в папку с проектом.

В папке с проектов выполните команду:
~~~~~~{.sh}
  git clone https://github.com/ItQuasarOrg/FontAwesomeGetChar.git
~~~~~~

## Использование (QML):
~~~~~~{.qml}
  import QtQuick 2.4
  import "FontAwesomeGetChar"
 
  FontLoader {
    source: "fontawesome-webfont.ttf"
  }
 
  Text {
    text: FontAwesomeGetChar.getChar("fa-user")
    font.family: "FontAwesome"
  }
~~~~~~

## Использование (JavaScript):
~~~~~~{.js}
  var char = getChar("fa-user") //возвращает юникод символ для иконки с именем "fa-user"
~~~~~~
