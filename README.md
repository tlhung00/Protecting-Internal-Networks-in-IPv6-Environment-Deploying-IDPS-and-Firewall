# Protecting-Internal-Networks-in-an-IPv6-Environment-Deploying-IDPS-and-Firewall

## Introduction
  
  This project aims to implement an internal network protection system in an IPv6 environment, focusing on integrating the pfSense firewall and the Intrusion Detection and Prevention System (IDPS) Snort, configured in inline mode to detect and prevent intrusion attempts.

## Deployment Model

The system consists of the following key components:

  pfSense: Firewall that controls traffic flow between the internal network and external networks.
  
  Snort (IDPS): Monitors and detects attacks in an IPv6 environment.
  
  Splunk (SIEM): Log management and analysis tool to monitor and detect suspicious behavior.
  
  Test Environment: Deployed on GNS3 with routers, switches, virtual machines for pfSense, Snort, Splunk, and simulated attack machines.

## Key Features

  Integrates pfSense as a firewall to control network access.
  
  Configures Snort in inline mode to detect and block attacks.
  
  Implements test scenarios with attack simulations such as SQL Injection and DNS Flood.
  
  Analyzes security logs with Splunk.

## System Requirements

  GNS3 for network simulation.
  
  pfSense as the firewall.
  
  Snort for traffic monitoring.
  
  Splunk for log analysis.
  
  Ubuntu/Kali Linux virtual machines for deployment and attack simulation.

## Installation Guide

  1. Configure GNS3 with network components like routers, switches, and pfSense firewall.
  
  2. Install and configure pfSense for network traffic management.
  
  3. Deploy Snort on an Ubuntu virtual machine to monitor and prevent attacks.
  
  4. Install Splunk to collect and analyze logs from Snort and pfSense.
  
  5. Execute test scenarios with SQL Injection and DNS Flood attacks to assess system effectiveness.

## Results

  The system successfully detects and prevents Time-based SQL Injection and DNS Flood attacks.
  
  pfSense ensures traffic control and protects the system against unauthorized access.
  
  Splunk aids in monitoring logs and providing detailed security event reports.

## Future Development
  
  Integrating SIEM to enhance security event monitoring.
  
  Applying Machine Learning to improve attack detection capabilities.
  
  Testing Suricata as an alternative to Snort for performance evaluation.
  
  Researching SDN integration to improve network security flexibility.
