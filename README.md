# Spotify_playlist_ReactNative_GraphQL

Install any code editor of your choice (e.g.- Microsoft Visual Code, atom etc)


## Windows
**1. Download Install Node.js** *(https://nodejs.org/en/)* **(LTS Version Recommended)** *(https://git-scm.com/downloads)* <br/>

**2. Open Node.js Command Prompt and type**
```
 node -v
 npm –v
``` 
**3. Install Expo Client using Node.js Command Prompt** *(https://expo.io/)*
```
  npm install -g expo-cli (or) sudo npm install expo-cli --global --unsafe-perm
```  

## Mac
**1. Install Xcode from App Store or update to the latest version if already installed** (https://itunes.apple.com/ae/app/xcode/id497799835?mt=12)

**2. Open Terminal and Install Homebrew (https://brew.sh) using the following command**
```
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
**3. Install Watchman**
```
  brew install watchman
```
**4. Install node**
```
  brew install git
  brew install node
```
 *Check node & npm version*
 ```
    node -v
    npm -v
 ```
**5. Install React Native**
```
  sudo npm install -g react-native-cli
```
**6. Install Expo Client**
```
  sudo npm install expo-cli --global --unsafe-perm
```


## Expo Client Mobile Application
**iPhone -** *https://itunes.apple.com/us/app/expo-client/id982107779?mt=8* <br/>
**Android -** *https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en*

## Setting up the Project
**1. Open Terminal/Command Prompt and go to the directory where you want to store the project**
```
 cd Desktop
```
**2. Create a blank expo template (Refer Installation Steps above for Expo) and Select blank template and type name of the project as Spotify Playlist**
```
 expo init spotify-playlist
```
```
  Read more: https://docs.expo.io/versions/latest/workflow/configuration/ › 50% completed
 {
   "expo": {
     "name": "Spotify Playlist",
     "slug": "spotify-playlist"
   }
 }
```
**3. Open the folder & Install Apollo Boost, React Apollo & GraphQL using Node.js Command Prompt**
```
  cd spotify-playlist
  npm install --save apollo-boost react-apollo graphql-tag graphql
```

**4. Download the fonts from (https://github.com/mridulrb/Spotify-Playlist-ReactNative-GraphQL/blob/master/assets/gibson-bold.ttf?raw=1) & (https://github.com/mridulrb/Spotify-Playlist-ReactNative-GraphQL/blob/master/assets/gibson-regular.ttf?raw=1).**<br/>
<br/>
**5. Now, Open the folder spotify-playlist/assets using Finder(Mac) & Windows Explorer(Windows) and move the fonts in this folder** <br/>
<br/>
**6. Right-Click Open the file App.js using any Code Editor Installed and add the code from the file App.js in this Repository and save it** <br/>
<br/>
**7. Open (https://pm5wl5l3r0.sse.codesandbox.io/) in browser or fork the repository from (https://codesandbox.io/s/pm5wl5l3r0) and edit the GraphQL dataset with your preferences** <br/>
<br/>
**8. Go back to Terminal/Command Prompt and type** <br/>
```
  npm start
```
**9. Scan the QR Code on iPhone using Camera App and Android using Expo App (Connect the Computer and Mobile on the same network)**

