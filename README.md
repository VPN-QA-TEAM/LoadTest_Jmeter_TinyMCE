# Load Testing TinyMCE Editor using JMETER Tools

## Overview
This is a load testing the TinyMCE Editor in Portal Sekolah Web using Jmeter Tools

## Tools and Technologies
**JMETER**: The Apache JMeter™ application is open source software, a 100% pure Java application designed to load test functional behavior and measure performance. It was originally designed for testing Web Applications but has since expanded to other test functions.

### Prerequisites </br>
**Java 11**: Make sure Java 11(minimum version) is installed on your system.</br>
**Jmeter**: Make sure apache jmeter version 5.6.3 is installed on your system.</br>

### How to run the load test
1. Clone the repository </br>
   ```git clone https://github.com/VPN-QA-TEAM/LoadTest_Jmeter_TinyMCE.git```
   
2. Open Terminal, run this command below :  
   - ```cd path_to\apache-jmeter-5.6.3\bin```
   - ```jmeter -n -t D:\PortalSekolah_TinyMCE.jmx -l D:\LogReport\log.csv -e -o D:\HTMLReport```
   ![image](https://github.com/VPN-QA-TEAM/LoadTest_Jmeter_TinyMCE/assets/146044337/c77adb0c-d245-45d3-8372-1d6d824a6b57)
   **_Command Explanation :_**</br>
     _-n : Run JMeter in non-GUI mode (no graphical interface).</br></br>
     -t : D:\PortalSekolah_TinyMCE.jmx : Specifies the JMeter test file to run (in this example, PortalSekolah_TinyMCE.jmx).</br></br>
     -l : D:\LogReport\log.csv : Specifies the log file where the test results will be saved (in this example, D:\LogReport\log.csv).</br></br>
     -e : command to generate an HTML report after the test has finished running.</br></br>
     -o : D:\HTMLReport : Specifies the output directory for HTML reports. However, this command is incomplete because after -o it must be followed by the output directory path.</br>_

3. Open report index.html in the HTMLReport directory
   
## Snapshot of Report
![image](https://github.com/VPN-QA-TEAM/LoadTest_Jmeter_TinyMCE/assets/146044337/2eec33bd-b48d-4c3a-82e2-354435b8030e)


Thank You !


