# Cybersecurity Lab Management

## Student Name

FAJAR FATIMA

## Student ID

26K-2024

## Project Description

This project is a C-based prototype for managing basic information about a university cybersecurity laboratory. The program collects information about laboratory equipment, security tools, and software costs, then calculates the total investment required for the lab.

## Input

The program asks the user to enter:

* Lab name
* Number of computers
* Number of network devices
* Number of security tools
* Cost per computer
* Cost per network device
* Annual security software cost

## Processing

The program calculates:

* Computer Cost = Number of Computers × Cost per Computer
* Network Cost = Number of Network Devices × Cost per Network Device
* Total Lab Investment = Computer Cost + Network Cost + Software Cost

## Output

The program generates a formatted cybersecurity lab report showing:

* Lab name
* Number of computers
* Number of network devices
* Number of security tools
* Computer cost
* Network device cost
* Software cost
* Total lab investment

## How to Compile

Using a C compiler such as GCC:

```bash
gcc cyber_lab.c -o cyber_lab
```

Then run the program:

```bash
./cyber_lab
```

On Windows, the executable can be run as:

```bash
cyber_lab.exe
```

## Sample Output

```text
========================================
       CYBERSECURITY LAB REPORT
========================================
Lab Name : Cyber Security Lab

Computers : 30
Network Devices : 8
Security Tools : 12
Computer Cost : 3000000.00
Network Device Cost : 400000.00
Software Cost : 500000.00
----------------------------------------
Total Lab Investment : 3900000.00
----------------------------------------
========================================
```
