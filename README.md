# Data-Collector-Sets
Performance Monitor to collect data on important server resources like CPU, Memory, Disk, and Network Interface.

Learning Outcomes
After completing this exercise, I will be able to:

- Create Data Collector Sets
- Create a Schedule
### My  Devices: I will be using the following devices in this lab.
USING VIRTUAL MACHINES WINDOW SERVER 2019 - DOMAIN SERVER, AND WINDOWS SERVER 2019 - DOMAIN MEMBER

Task 1 - Create Data Collector Sets
Data collector sets is a useful feature of Performance monitor as it allows administrators to collect data unattended on important server resources. The collected statistics from the target server can be imported into a chart view for further analysis.

In this step, you will configure the data collector set and capture statistics on hardware components.

Step 1
Ensure you have powered on the required devices and connect to PLABDM01.

Go to Server Manager, then Tools menu, and select Performance Monitor.
Step 2
Expand Data Collector Sets, right-click User Defined, select New, and then select Data Collector Set.

![image](https://github.com/kalejcamto/Data-Collector-Sets/assets/101201140/5d02d516-5c46-4fe1-bf30-716f0d53a2d6)

![image](https://github.com/kalejcamto/Data-Collector-Sets/assets/101201140/989d0210-537a-47ca-b3cd-70b343b5ca75)

Step 3
In the Create New Data Collector Set wizard, On the How would you like to create this new data collector set? page, in Name textbox type Off Peak Usage Test.

Select Create manually (Advanced) option. Click Next.


![image](https://github.com/kalejcamto/Data-Collector-Sets/assets/101201140/610d0397-15ab-4e58-ab1f-3fabf4f1a4d7)

Step 4
On the What type of data do you want to include? page, Create data logs is selected by default. Select Performance counters.

Click Next.


![image](https://github.com/kalejcamto/Data-Collector-Sets/assets/101201140/e49f971a-0082-4844-824b-42eae53ee4ed)

Step 5
On the Which performance counters would you like to log? page, click Add.

![image](https://github.com/kalejcamto/Data-Collector-Sets/assets/101201140/59c9e107-5d0e-4e7e-8674-f7dc5592118f)

to be continued












