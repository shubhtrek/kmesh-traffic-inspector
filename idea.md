# Kmesh: 

Real-time Traffic Inspection and Debugging CLI

## Description

Kmesh provides high-performance traffic management using eBPF, but debugging live traffic behavior—especially for long-lived TCP connections—remains challenging. Currently, metrics are mainly available after a connection is closed, making real-time analysis difficult.

This project aims to develop a lightweight CLI-based debugging tool for Kmesh to inspect live service-to-service traffic, monitor ongoing TCP connections, and view intermediate metrics such as latency, errors, and throughput.

## Expected Outcome

- CLI tool for real-time traffic inspection  
- Monitoring of active TCP connections with intermediate metrics  
- Improved debugging and observability for Kmesh  
- Basic documentation and usage guide  

## Recommended Skills

- Golang  
- Kubernetes
- Basic networking knowledge (TCP/IP)  
- Familiarity with Kmesh  

