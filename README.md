# 📡 Network Monitoring Project with SolarWinds NPM

> Implementation of a real-time network performance monitoring system using **SolarWinds Network Performance Monitor (NPM)**, combined with network simulation in GNS3 and VMware.

---

## 🎯 Project Objectives

- Build a simulated network topology with multiple nodes (routers, switches, servers)

- Configure performance monitoring with **SolarWinds NPM**

- Enable automatic email alerts when failures or overloads occur

- Test real-world scenarios such as node down, CPU overload, and connectivity loss

---

## 🛠 Technologies & Tools

| Component        | Technology / Tool             |
|------------------|-------------------------------|
| Network Monitoring    | SolarWinds Network Performance Monitor (NPM) |
| Network Simulation    | GNS3 + VMware (Windows Server) |
| Monitoring Protocols| SNMP (v2, v3), ICMP          |
| Email Alerts   | SMTP configured in SolarWinds |
| Client Devices | Windows, Linux (agentless or SNMP-enabled) |

---

## 🧪 Implemented Features

- Monitoring of network device performance (CPU, RAM, availability)

- Alerts for connectivity loss and resource overload

- Centralized management of multiple network nodes from a single dashboard
  
- Real-time performance charting and visualization
  
- Scheduled reports and detailed statistics

---

## 🖼️ Illustrations

<p align="">
  <strong>SolarWinds Dashboards:</strong><br>


  ![DB](https://github.com/MHabc/solarwinds-network-monitoring/blob/master/Picture2.png)


  <strong>Alert Configuration:</strong><br>
  
  ![alert](https://github.com/MHabc/solarwinds-network-monitoring/blob/master/Picture3.png)


  <strong>Simulated Topology on GNS3:</strong><br>
  
  ![topology](https://github.com/MHabc/solarwinds-network-monitoring/blob/master/Picture1.png)
  
</p>

---

## 📁 Project Structure

```
SolarWinds_Project/
├── report/
├── gns3_project/           # GNS3 configuration files
├── README.md
```

---


## ▶️ Demo video 
* Alert_Demo: Alert_Demo_Full.mp4
* CPULoad_Demo: CPULoad_Demo_Full.mp4
* Discovery_Demo: Discovery_Demo_Full.mp4 
