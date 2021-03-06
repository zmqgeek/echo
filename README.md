# Echo

Our Echo Tutorial covers user-guide, examples with screenshots to make it easy for beginners to set up our tools and test Android apps.
# Contact
If you have any questions,please contact me by email 2534545103@qq.com
## `Step 1:Setup Echo tool Environment`
you need to install eclipse、Android and appium.<br>

Detailed installation steps refer to the following link: http://www.automationtestinghub.com/appium-tutorial/
### If you have installed these Environment, or looking only for specific details, then you can skip through the step and focus on those which you are not installed.<br><br><br>

## `Step 2:Import this tool`

### Step 2.1:Download the project and import.<br>
1. Download the project by github.<br>

<div align=center><img width="600" height="301" src="https://github.com/zmqgeek/Echo/blob/master/img/5.png"/></div><br>

Clone or download->Download ZIP->unzip in your windows<br>

2. Import this project as gradle at eclipse.(Make sure your eclipse has gradle installed)<br>

(1) Open eclipse->File->new->other<br>

The following window pops up to see if there is a gradle project<br>

<div align=center><img width="600" height="499" src="https://github.com/zmqgeek/Echo/blob/master/img/6.png"/></div><br>

(2) If you don't have gradle installed, create gradle in eclipse.<br>

Help->Eclipse Marketplace    Pop up the following dialog<br>

<div align=center><img width="600" height="405" src="https://github.com/zmqgeek/Echo/blob/master/img/7.png"/></div><br>

(3) Gradle user home configuration, which is the installation path of your gradle.<br>

<div align=center><img width="600" height="487" src="https://github.com/zmqgeek/Echo/blob/master/img/8.png"/></div><br>

(4) Import the source code downloaded above.<br>

File->Import->Gradle->Existing Gradle Project<br>

<div align=center><img width="600" height"545" src="https://github.com/zmqgeek/Echo/blob/master/img/9.png"/></div><br><br>

### Step 2.2:Modify configuration file config.properties
Modify the following lines at config.properties

<div align=center><img src="https://github.com/zmqgeek/Echo/blob/master/img/1.png"/></div>
<div align=center><img src="https://github.com/zmqgeek/Echo/blob/master/img/2.png"/></div><br>

1: yours Android app directory.(You need to create a file in advance to store the apk you need to test.)<br>

4: Change to yours output directory.(You need to create a output file to save files generated during the test.)<br>

10: Change to yours JVM Configurations.(Generally this is the default, but you can modify it according to your needs.)<br>

11:Check if this path is consistent with your system-activities file path，if the inconsistency is changed to your path.<br><br>

### Step 2.3:Modify configuration file Settings.gradle<br>
<div align=center><img src="https://github.com/zmqgeek/Echo/blob/master/img/%E5%9B%BE%E7%89%873.png"/></div><br>

Check if this path is consistent with your project file path，if the inconsistency is changed to your path.<br><br><br>

## `Step 3:Testing`

### Step 3.1:Create a Android Emulator named Nexus_5_API_19 and open it.<br>
Choose Create Device->named Nexus_5_API_19<br>

<div align=center><img width="600" height="322" src="https://github.com/zmqgeek/Echo/blob/master/img/10.png"/></div><br>

(2) run it (Click the start button)

<div align=center><img width="600" height="118" src="https://github.com/zmqgeek/Echo/blob/master/img/11.png"/></div><br><br>

### Step 3.2:Open appium desktop. 
(1) Double-click the appium shortcut for your windows desktop.<br>

<div align=center><img  width="600" height="453" src="https://github.com/zmqgeek/Echo/blob/master/img/12.png"/></div><br>

(2)Choose Advanced->Check Allow Session Override. The following interface appears.<br>

<div align=center><img width="600" height="561" src="https://github.com/zmqgeek/Echo/blob/master/img/13.png"/></div><br><br>

### Step 3.3:testing app

1.Run gradle tasks test

<div align=center><img width="600" height="297" src="https://github.com/zmqgeek/Echo/blob/master/img/%E5%9B%BE%E7%89%874.png"/></div><br>

2.You will see the program running as follows.<br>

<div align=center><img width="600" height"415" src="https://github.com/zmqgeek/Echo/blob/master/img/14.png"/></div><br>

3.After the stopped in bug state, you will be able to see the following file generated from the corresponding output folder.<br>

<div align=center><img width="600" height="381" src="https://github.com/zmqgeek/Echo/blob/master/img/15.png"/></div><br>

4.Calculate the shortest path replay the error based on the generated file.<br>

<div align=center><img width="600" height="432" src="https://github.com/zmqgeek/Echo/blob/master/img/16.png"/></div><br>
