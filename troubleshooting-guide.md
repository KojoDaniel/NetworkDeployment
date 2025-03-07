# Network Troubleshooting Guide

### Common Network Issues & Fixes
1️⃣ **Slow Internet?**  
   - Check bandwidth usage with `iftop`  
   - Prioritize traffic using QoS (Quality of Service)  

2️⃣ **Frequent Disconnections?**  
   - Check for interference on WiFi channels  
   - Enable VLANs for traffic segmentation  

3️⃣ **Firewall Blocking Apps?**  
   - Verify firewall rules using `iptables -L` (Linux) or `show access-lists` (Cisco)  
