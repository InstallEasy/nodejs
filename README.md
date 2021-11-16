# NodeJS

This repository contains documentation for easy installation the **[NodeSource](https://nodesource.com)** **[Node.js](http://nodejs.org)** Binary Distributions via .rpm and .deb packages as well as their setup and support scripts.

Installation script is work:

    ./script.sh current

and after installation only in this `current` need to install `npm`

or with version

    ./script.sh 16 

or if you want tls

    ./script.sh tls

or fast download and auto start installation

     bash <(curl -sLhttps://raw.githubusercontent.com/InstallEasy/nodejs/main/script.sh) current
