# advanced-shodan-queries
Curated list of advanced Shodan queries for discovering exposed assets, dashboards, and services.


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
