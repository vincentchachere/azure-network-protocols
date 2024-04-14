<p align="center">
<img width="1000" alt="isolated" src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

# Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

## Operating Systems Used

- Windows 10 (21H2)
- Linux Ubuntu Server 20.04

## High-Level Steps

- Create Resources
- Install Wireshark
- Observe Differing Network Protocols suh as:
  - ICMP Traffic
  - SSH Traffic
  - DHCP Traffic
  - DNS Traffic
  - RDP Traffic

## Additional Resources

- For more information on Azure Networking Products click [here](https://azure.microsoft.com/en-us/products/category/networking)

## Actions and Observations

### 1. ) Create your Resource Group

- 

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/8817b441-20c7-4402-96ba-93590df8d535"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/5ff75287-da94-4e53-824e-7111f412c7a0"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/6b0736f2-dd6a-4ed3-9e5b-a72570a4a46e"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/73aa9fd5-42d8-4590-8596-58cd61ddf67d"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/25da2c2f-598f-4bf6-b3e2-9ef5a7a8c773"><br>

***

### Create your 1st Virtual Machine for this Lab

- 

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/9101c495-f928-4aa1-8e9e-6008ce9e1a57"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/81279c8d-be5a-4e55-a046-9c197e84dbf4"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/4ff4a264-ad0c-47f3-9cc3-0ce2877df31b"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/0ce9eed6-efda-4359-a53c-7e2d1895059b"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/5757c155-fc86-4cc0-aa29-10b699d26489"><br>

***

### Create your 2nd Virtual Machine for this Lab

- 

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/9101c495-f928-4aa1-8e9e-6008ce9e1a57"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/8ebb6247-7180-4317-8c5a-0f16e49a68e2"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/azure-network-protocols/assets/161680745/913067ed-149d-459a-a4b1-033ace987c37"><br>
<p align="center">
<img width="800" alt="isolated" src=""><br>
<p align="center">
<img width="800" alt="isolated" src=""><br>
<p align="center">
<img width="800" alt="isolated" src=""><br>
<p align="center">
<img width="800" alt="isolated" src=""><br>
<p align="center">
<img width="800" alt="isolated" src=""><br>
<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### 

- 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***
