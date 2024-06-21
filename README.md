# Load Testing TinyMCE Editor using JMETER Tools

## Overview
This is a load testing the TinyMCE Editor in Portal Sekolah Web using Jmeter Tools

## Tools and Technologies
**JMETER**: The programming language used for writing the test scripts.

### Prerequisites
**Java 11**: Make sure Java 11(minimum version) is installed on your system.
**Jmeter**: Make sure apache jmeter version 5.6.3 is installed on your system.

### How to run the load test
1. Clone the repository
   git clone https://github.com/VPN-QA-TEAM/LoadTest_Jmeter_TinyMCE.git
   
2. Open Terminal, run this command below :  
   - ```cd path_to\apache-jmeter-5.6.3\bin```
   - ```jmeter -n -t D:\PortalSekolah_TinyMCE.jmx -l D:\LogReport\log.csv -e -o D:\HTMLReport```
   ![image](https://github.com/VPN-QA-TEAM/LoadTest_Jmeter_TinyMCE/assets/146044337/c77adb0c-d245-45d3-8372-1d6d824a6b57)
   **Command Explanation :**
     -n : Run JMeter in non-GUI mode (no graphical interface).
     -t : D:\PortalSekolah_TinyMCE.jmx : Specifies the JMeter test file to run (in this example, PortalSekolah_TinyMCE.jmx).
     -l : D:\LogReport\log.csv : Specifies the log file where the test results will be saved (in this example, D:\report.csv).
     -e : command to generate an HTML report after the test has finished running.
     -o : D:\HTMLReport : Specifies the output directory for HTML reports. However, this command is incomplete because after -o it must be followed by the output directory path.

## Snapshot of Report
![image](https://github.com/VPN-QA-TEAM/LoadTest_Jmeter_TinyMCE/assets/146044337/2eec33bd-b48d-4c3a-82e2-354435b8030e)


Thank You !


