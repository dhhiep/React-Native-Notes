### System
    OS X El Capitan 10.11.6

### Steps
##### 1. Install Brew (https://brew.sh/) 
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"


##### 2.Install Node.js
    brew install node
##### 3. Install React Native
    npm install –g react-native-cli

##### 4. Install Watchman
    brew install watchman
##### 5. Install Flow
    brew install flow

##### 6. Install Xcode
1. Vào App Store rồi cài Xcode
2. Mở Xcode lên vào Preference (phím tắt Command + ,) > Locations, trường Command Line Tool chọn Xcode xxx (xxx là version)

##### 7. Init React Native Project and run on iOS simulator
    react-native init hello-world
    cd hello-world
    react-native run-ios

##### 8. Q & A

###### Q1: Project init fails with unexpected token (TerminalClass.js:141 SyntaxError: Unexpected token ...)

    sudo npm install -g npm
    sudo npm cache clean -f
    sudo npm install -g n
    sudo n stable

###### Q2: El Capitain Error: EACCES: permission denied, opeccn '/Users/milinka/.babel.json'
    sudo chmod 777 ~/.babel.json

