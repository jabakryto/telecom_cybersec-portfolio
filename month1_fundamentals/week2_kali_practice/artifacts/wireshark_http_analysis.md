 HEAD
# Wireshark HTTP Analysis
## Filter
http.request.method == "GET"
DNS
http
tcp.port==80
## Observation
- Request to `/dvwa/login.php`
- User-Agent: `Mozilla/5.0`
- No sensitive data in URL (good)
> All IPs anonymized: 192.0.2.0/24


Wireshark HTTP Analysis
Filter
http.request.method == "GET"
Observation
Request to /dvwa/login.php
User-Agent: Mozilla/5.0
No sensitive data in URL (good)
All IPs anonymized: 192.0.2.0/24
EOF 

 477d6c4 (Month 2: Week 5 — SOC analysis (MITRE ATT&CK, Sigma, log analysis))
