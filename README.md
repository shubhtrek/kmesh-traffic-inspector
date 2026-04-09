# Kmesh: Real-time Traffic Inspection and Debugging CLI

This repository contains my research and initial design ideas for improving debugging and observability in Kmesh.

## Idea

I am proposing a CLI-based tool that helps developers inspect real-time traffic inside Kmesh.

## Problem

While exploring Kmesh, I noticed that metrics for TCP connections are mostly available only after the connection is closed.

This makes it difficult to:
- Debug long-lived connections  
- Understand real-time traffic behavior  
- Diagnose issues while services are still communicating  

## Proposed Solution

A CLI tool that allows developers to:

- View live service-to-service traffic  
- Track ongoing TCP connections  
- See intermediate metrics like latency, errors, and throughput  
- Understand request flow in real time  

## Expected Outcome

- CLI tool for real-time traffic inspection  
- Monitoring of active TCP connections with intermediate metrics  
- Improved debugging and observability for Kmesh  
- Basic documentation and usage guide  

## Why this matters

Kmesh is focused on performance using eBPF, but debugging and observability are still challenging.

This tool can:
- Improve developer experience  
- Help contributors debug faster  
- Complement the existing metrics system  

## Repo Structure

- `docs/` → detailed research and design  
- `examples/` → sample CLI output  