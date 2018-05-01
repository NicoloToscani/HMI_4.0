# HMI-4.0
Example of integration between OT and IT.

## Description

In this project we will show how to connect the OT (Operational Technology) factory level with the IT (Information Techlology) management level.
For this example, a human machine interface (HMI) is used to read a temperature detected by a SIEMENS S7-1200 PLC and send the value to Azure IoT Hub.

## HMI
The temperature value is read by the PLC using a WPF application with MVVM pattern, using the Sharp7 library.
![](https://user-images.githubusercontent.com/12815808/39473065-49452cf2-4d4d-11e8-8c8b-02bcb5a2dae1.png)
![](https://user-images.githubusercontent.com/12815808/39473417-136fd274-4d4f-11e8-8f4c-a73068da4fb2.png)
