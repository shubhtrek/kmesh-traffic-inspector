# Problem Statement

Kmesh provides metrics for service communication, but currently:

- Metrics are often available only after a TCP connection is closed  
- Long-lived connections cannot be observed in real time  
- Debugging live traffic is difficult  

This creates challenges for developers trying to:
- Understand traffic flow  
- Debug issues  
- Monitor ongoing communication  

There is a need for better real-time visibility into Kmesh traffic.