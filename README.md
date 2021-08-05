# Unity Messenger
A powerful multi-featured chat application built on top of Google's Android &amp; ML technologies

- Detailed Readme will be updated soon.

## Instructions to run

* Pre-requisites:
	-  Android Studio v4.0+
	-  A working Android physical device or emulator with USB debugging enabled
	-  Node.js
	-  NPM

* Directions to setup/install [For Android]
	- Clone this repository to your local folder using Git bash:
	```bash
	git clone https://github.com/ydasc815/unity-messenger
	```
	- Open this project from Android Studio
	- Connect to an Android physical device or emulator
	- To install the app into your device, run the following using command line tools
	```bash
	gradlew installDebug
	```
* Directions to setup/install [For Backend]
  - Clone this repository using the previously mentioned instructions
  - From CMD, execute the following:
  ```bash
  $ cd unity-messenger
  $ touch .env
  $ cp .env.example .env
  ```
  - Setup environment variables 
  ```bash
  $ npm i
	``` 

* Directions to execute [For Android]
	-  To launch hands free, run the following using command line tools
	```bash
	adb shell monkey -p com.aditya.unitymessenger -c android.intent.category.LAUNCHER 1
	```
  
* Directions to execute [For Backend]
  -   Execute the following from CMD:
  ```bash
  $ npm run dev
  ```
  
## Contributors

* [Aditya Pandey](https://github.com/ydasc815)
* [Ishita Jaiswal](https://github.com/ishitajaiswal4m)
* [Shekhar Pandey](https://github.com/shekharme88)
