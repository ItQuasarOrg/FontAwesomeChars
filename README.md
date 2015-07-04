# FontAwesomeChars
Simple JavaScript script for get font Awesome unicode char for his name.

##Install
Download font Awesome from http://fortawesome.github.io/Font-Awesome/ and copy "fontawesome-webfont.ttf" to project folder.

In project folder run command:
~~~~~~{.sh}
  git clone https://github.com/ItQuasarOrg/FontAwesomeChars.git
~~~~~~

##Usage (QML):
~~~~~~{.qml}
  import QtQuick 2.4
  import "FontAwesomeChars"
 
  FontLoader {
    source: "fontawesome-webfont.ttf"
  }
 
  Text {
    text: FontAwesomeChars.getChar("fa-user")
    font.family: "FontAwesome"
  }
~~~~~~

##Usage (JavaScript):
~~~~~~{.js}
  var char = getChar("fa-user") //return unicode char for icon "fa-user"
~~~~~~
