# Echo

Our Echo Tutorial covers user-guide, examples with screenshots to make it easy for beginners to set up our tools and test Android apps.

## Step 1:Setup Echo tool Environment
you need to install eclipse、Android and appium.
Detailed installation steps refer to the following link: http://www.automationtestinghub.com/appium-tutorial/
### If you have installed these Environment, or looking only for specific details, then you can skip through the step and focus on those which you are not installed.


## Step 2:Import this tool

### Step 2.1:Download the project and import.
1. Download the project by github.<br>
<div align=center><img width="150" height="150" src="https://github.com/zmqgeek/Echo/blob/master/img/5.png"/></div>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/5.png)<br>
Clone or download->Download ZIP->unzip in your windows<br>
2. Import this project as gradle at eclipse.(Make sure your eclipse has gradle installed)<br>
(1) Open eclipse->File->new->other<br>
The following window pops up to see if there is a gradle project<br>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/6.png)<br>
(2) If you don't have gradle installed, create gradle in eclipse.<br>
Help->Eclipse Marketplace    Pop up the following dialog<br>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/7.png)<br>
(3) Gradle user home configuration, which is the installation path of your gradle.<br>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/8.png)<br>
(4) Import the source code downloaded above.<br>
File->Import->Gradle->Existing Gradle Project<br>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/9.png)<br>

### Step 2.2:Modify configuration file config.properties
Modify the following lines at config.properties
![Image text](https://github.com/zmqgeek/Echo/blob/master/img/%E5%9B%BE%E7%89%871.png)
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/%E5%9B%BE%E7%89%872.png)

1: Change to yours Android app directory.(You need to create a file in advance to store the apk you need to test.)<br>
2: Change to yours Instrumented app directory.<br>
3: Change to yours android.jar location.<br>
4: Change to yours output directory.(You need to create a output file to save files generated during the test.)<br>
5: Change to yours files required by FlowDroid.<br>
6: Change to yours current project location.<br>
7: Change to yours the location of adb tool.<br>
8: Change to yours Android SDK location.<br>
9: Change to yours SDK tool-version.<br>
10: Change to yours JVM Configurations.(Generally this is the default, but you can modify it according to your needs.)<br>
11:Check if this path is consistent with your system-activities file path，if the inconsistency is changed to your path.<br>

### Step 2.3:Modify configuration file Settings.gradle<br>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/%E5%9B%BE%E7%89%873.png)
Check if this path is consistent with your project file path，if the inconsistency is changed to your path.<br>


## Step 3: Testing  

### Step 3.1:Create a Android Emulator named Nexus_5_API_19 and open it.
Choose Create Device->named Nexus_5_API_19<br>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/10.png)<br>
(2) run it (Click the start button)
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/11.png)<br>

### Step 3.2:Open appium desktop. 
(1) Double-click the appium shortcut for your windows desktop.<br>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/12.png)<br>
(2)Choose Advanced->Check Allow Session Override. The following interface appears.<br>
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/13.png)<br>

### Step 3.3:testing app
![Image_text](https://github.com/zmqgeek/Echo/blob/master/img/%E5%9B%BE%E7%89%874.png)
Run gradle tasks test

