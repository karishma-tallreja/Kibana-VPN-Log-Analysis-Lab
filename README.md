# Kibana-VPN-Log-Analysis-Lab

A hands-on log analysis lab using the **Kibana Discover tab** to filter, search, and identify anomalies in VPN logs via TryHackMe’s **Kibana Discover** lab.

---

## 🎯 Objective

- Explore and search VPN logs in Kibana  
- Apply filters and build custom field tables  
- Identify suspicious behavior and anomalies  
- Analyze log spikes and high-traffic users

---

## 🛠️ Tools Used

- **Kibana** (Discover tab)  
- **Elasticsearch**  
- **vpn_connections index**  
- **TryHackMe AttackBox**

---

## 🧠 Skills Learned

- Log filtering & KQL searches  
- Creating custom tables in Kibana  
- Identifying anomalies & spikes  
- Time-range based log analysis  
- Real-time SOC analyst practices

---

## 📸 Screenshots

## **1. Elastic Stack Homepage**  
<img src="https://i.imgur.com/eQ1qoAI.png" width="600"/>


## **2. Kibana Home - Analytics Page**  
<img src="https://i.imgur.com/4heOhLA.png" width="600"/>


## **3. Dashboard + Discover Tab Interface**  
<img src="https://i.imgur.com/9AYqEzC.png" width="600"/>


## **4. Time Filter Set: Dec 31, 2021 – Feb 2, 2022**  
<img src="https://i.imgur.com/l69eCfs.png" width="600"/>

## **5. Index Pattern + Field (sourceIP selected)**  
<img src="https://i.imgur.com/Afm8JEf.png" width="600"/>

## **6. Add Filter Interface**  
<img src="https://i.imgur.com/QdyZKbi.png" width="600"/>

## **7. Created Table View (IP, UserName, Source_Country)**  
<img src="https://i.imgur.com/3VGgLjN.png" width="600"/>

## **8. Max Traffic User (James)**  
<img src="https://i.imgur.com/oiLow4s.png" width="600"/>

## **9. Source IP for Emanda (107.14.1.247)**  
<img src="https://i.imgur.com/QK9jMOH.png" width="600"/>

## **10. Spike on Jan 11 – IP Identified**  
<img src="https://i.imgur.com/JUBNPci.png" width="600"/>
<img src="https://i.imgur.com/AceCcMX.png" width="600"/>

## **11. Filtered Logs by IP Excluding New York**  
<img src="https://i.imgur.com/dN1roKK.png" width="600"/> 
<img src="https://i.imgur.com/TrL5aLD.png" width="600"/>
---

## ✅ Summary / Key Findings

- **2861 logs** found in target time range  
- **James** had the highest VPN traffic  
- Spike on **Jan 11** caused by IP `172.201.60.191`  
- **48** connections from IP `238.163.231.224` excluding New York  


