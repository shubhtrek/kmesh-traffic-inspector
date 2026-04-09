# Architecture Idea

The proposed system will work as follows:

Kmesh (eBPF Layer)
        ↓
Traffic Events / Metrics
        ↓
Kmesh API / Export Layer
        ↓
CLI Tool (User Interface)
        ↓
Developer Output

## Explanation

- Kmesh captures traffic using eBPF  
- Metrics/events are exposed via APIs or internal hooks  
- CLI tool fetches this data  
- Displays it in a simple, readable format  

This design keeps the tool lightweight and developer-friendly.