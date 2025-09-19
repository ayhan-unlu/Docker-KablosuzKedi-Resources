 root@1254e9833cbc:/opt/node-app#  history
    1  apt-get update
    2  apt-get install curl -y
    3  curl -sl https://deb.nodesource.com/setup_10.x | bash
    4  apt-get install nodejs -y
    6  cd opt
    8  mkdir node-app
    9  cd node-app
   14  echo 'console.log("nodejsapp from ubuntu ... ");' > index.js
   17  node index.js