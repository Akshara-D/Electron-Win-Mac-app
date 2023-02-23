#**SAMPLE DEKSTOP APP THAT RUNS IN WINDOWS AND MACOS**

**This is a simple cross platform app built using Electron framework with nodejs** <br>

Created a CICD process that involves <br>
1. Builds the app in windows and macOs <br>
2. Sign's the .exe and .app files
3. Sends .app files to notarizing process
4. Pipeline trigger condition is set only when there is a push in master branch
5. Im Asssuming the keys and credentials for the signing process to be as a dummy variables. The other pipeline tasks are performed and getting the relevent executable files i.e electron-app.app , electron-app.exe

PIPELINE FILE : (https://github.com/Akshara-D/Electron-Win-Mac-app/blob/master/.github/workflows/mac-win-master.yml)

**USED azure secrets to store all keys/credentials needed in this pipeline**


