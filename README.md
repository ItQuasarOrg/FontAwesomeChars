# fontAwesomeGetChar.js
Simple JavaScript script for get font Awesome unicode char for his name.

##Install
In project folder run command:
~~~~~~{.sh}
  git clone https://github.com/ItQuasarOrg/FontAwesomeGetChar.git
~~~~~~

##Usage (JavaScript):
~~~~~~{.js}
  var char = getChar("fa-user") //return unicode char for icon "fa-user"
~~~~~~

##Usage (QML):
~~~~~~{.qml}
  import "FontAwesomeGetChar"

  Text {
    text: FontAwesomeGetChar.getChar("fa-user")
  }
~~~~~~
