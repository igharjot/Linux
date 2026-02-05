# Day-4 Task: Linux Practice Commands

---

## 1. Process Checks

ps -ef  
top  
pgrep ssh  

---

## 2. Service Checks

systemctl status ssh  
systemctl list-units --type=service --state=running  
systemctl restart ssh  

---

## 3. Log Checks

journalctl -u ssh  
journalctl -u ssh -n 50  
tail -n 50 /var/log/syslog  

---

## 4. Mini Troubleshooting Steps

pgrep ssh  
systemctl status ssh  
systemctl restart ssh  
journalctl -u ssh -xe  
systemctl status ssh

---
