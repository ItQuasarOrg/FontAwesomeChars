# fontAwesomeGetChar.js
Simple JavaScript script for get font Awesome unicode char for his name.

##Install
In project folder run command:
~~~~~~{.sh}
  git clone https://github.com/ItQuasarOrg/FontAwesomeGetChar.git
~~~~~~

##Usage (JavaScript):
~~~~~~{.js}
  var char = getChar("fa-user") // return unicode char for icon with name "fa-user"
~~~~~~

##Usage (QML):
~~~~~~{.qml}
  import "FontAwesomeGetChar" as FontAwesomeGetChar

  Text {
    text: FontAwesomeGetChar.getChar("fa-user")
  }
~~~~~~
