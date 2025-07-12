# advanced-shodan-queries
Curated list of advanced Shodan queries for discovering exposed assets, dashboards, and services.

# 🔥 ULTIMATE SHODAN DORKS – All-in-One Recon & OSINT Queries

> 👨‍💻 Curated by Aditya Kumawat – Cybersecurity Student  
> 🎯 Goal: Find exposed services, panels, logins, admin portals & misconfigurations using Shodan.  
> 📌 For educational and responsible disclosure purposes only.

---

## 🧠 Login Portals & Admin Panels

- title:"admin login"
- title:"Login" http.favicon.hash:-1654229048
- title:"Dashboard [Jenkins]"
- title:"phpMyAdmin" port:80
- http.title:"Welcome to OpenVPN Access Server"
- title:"webmin" port:10000
- title:"Apache Tomcat" port:8080
- title:"vSphere Web Client" ssl:true
- title:"Netdata dashboard" port:19999
- title:"Kibana" port:5601
- title:"Grafana" port:3000
- title:"Zabbix" port:80
- title:"Nginx Admin" port:8080

---

## 🌐 Open Directories & File Browsing

- "Index of /admin"
- "Index of /backup"
- "Index of /confidential"
- "Index of /config"
- "Index of /database"
- "Index of /uploads"
- "Index of /documents"

---

## 🎥 Webcams & Security Cameras

- port:554 has_screenshot:true
- port:81 "NETSurveillance WEB"
- port:8080 ispyconnect
- title:"IP Camera"
- "webcamXP 5" port:8080
- title:"DVR WebClient" port:8080
- "Server: Boa/0.94.14rc21"

---

## 🧰 Developer/IT Dashboards

- title:"Kibana" port:5601
- title:"Grafana" port:3000
- title:"ElasticSearch" port:9200
- title:"SonarQube" port:9000
- title:"Netdata dashboard"
- title:"Prometheus Time Series Collection"
- title:"Docker Registry"
- "Server: Docker Registry"

---

## 🔐 Product/Software-Based Panels

- title:"Jenkins" port:8080
- title:"phpMyAdmin" port:80
- title:"MongoDB Web" port:28017
- title:"Cisco" port:8080
- title:"Dahua Login" port:80
- title:"Zyxel" port:80
- title:"SonicWall - Virtual Office"
- title:"Plesk Login"
- title:"cPanel" port:2083

---

## 🚨 Vulnerable/Leaky Services

- product:"Elasticsearch" port:9200 -authentication
- product:"MongoDB" port:27017 -authentication
- product:"CouchDB" port:5984 -_config
- "XAMPP" "phpMyAdmin"
- "Server: Apache-Coyote/1.1"

---

## 🌍 Geo & ISP Targeting

- country:"IN" port:80
- org:"Airtel Broadband" port:23
- asn:13335 port:443
- city:"Mumbai" port:21
- net:"103.XX.XX.0/24"

---

## 🔍 Special/Weird Dorks

- port:80 "Set-Cookie: PHPSESSID="
- http.html_hash:2123213923
- ssl.cert.subject.CN:"*.gov.in"
- product:"Mikrotik" "Login"
- http.title:"Unauthorized Access"
- html:"Hikvision Digital Technology"

---

---

## ✍ Author

*Aditya Kumawat*  
Cybersecurity Student | Bug Bounty Learner  
🔗 [GitHub Profile](https://github.com/adityakumawat2005)

---


