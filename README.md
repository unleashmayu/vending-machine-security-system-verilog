# vending-machine-security-system-verilog
FSM-Based Security System for Vending Machines using Verilog HDL with Password Authentication and Tamper Detection.


# Security System for Vending Machine Using Verilog

## Overview

Vending machines are widely deployed in public locations and are often vulnerable to unauthorized access, theft, and physical tampering. This project presents a Verilog-based security system designed to improve the protection of vending machines through password authentication and sensor-based monitoring.

The system continuously monitors various security conditions and activates an alarm whenever unauthorized activity is detected.

The design was implemented using Finite State Machine (FSM) methodology and verified through simulation.

---

## Motivation

Traditional vending machines often rely on mechanical locks and basic security mechanisms. These approaches may not provide sufficient protection against tampering or unauthorized access.

This project explores how digital design techniques can be used to create a smarter and more reliable security system.

---

## Objectives

* Design a vending machine security system using Verilog HDL.
* Implement password-based authentication.
* Monitor machine status using multiple sensors.
* Detect unauthorized access attempts.
* Generate alarm signals when security violations occur.
* Verify functionality through simulation.

---

## Technologies Used

* Verilog HDL
* Xilinx ISE
* FSM Design Methodology
* CPLD/FPGA Platform

---

## System Components

### Password Authentication

Validates user credentials before allowing access to the vending machine.

### Door Monitoring

Detects unauthorized opening of the machine door.

### Vibration Detection

Monitors physical tampering attempts.

### Tilt Detection

Identifies abnormal movement or attempts to relocate the machine.

### Alarm System

Activates warning mechanisms whenever a violation is detected.

---

## Working Principle

The system continuously monitors all security inputs.

During normal operation:

1. User authentication is verified.
2. Sensor status is monitored.
3. Machine remains in a secure state.

When a violation occurs:

* Wrong password entered
* Unauthorized door opening
* Excessive vibration detected
* Machine tilt detected

The system immediately enters the alarm state and activates security alerts.

---

## FSM-Based Design

A Finite State Machine controls the complete operation of the system.

Major states include:

* Idle State
* Authentication State
* Access Granted State
* Monitoring State
* Alarm State

FSM implementation ensures predictable and reliable operation.

---

## Results

Simulation results confirmed:

* Successful password verification
* Proper FSM transitions
* Accurate sensor monitoring
* Reliable alarm activation
* Stable system behavior

---

## Applications

* Smart Vending Machines
* Electronic Lock Systems
* Secure Storage Units
* Automated Kiosks
* Access Control Systems

---

## Skills Demonstrated

* Verilog HDL
* FSM Design
* Digital Logic Design
* Hardware Verification
* FPGA/CPLD Development
* Simulation and Testing

---

## Future Improvements

* RFID Authentication
* Biometric Access Control
* GSM Alert Notifications
* IoT-Based Monitoring
* Mobile Application Integration

---

## Conclusion

This project demonstrates the design and implementation of a secure vending machine monitoring system using Verilog HDL. By combining password authentication, sensor monitoring, and FSM-based control, the design provides an effective solution for detecting and responding to unauthorized access and tampering attempts.
