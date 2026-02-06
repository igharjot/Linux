# Day 08 – Cloud Server Setup: Docker, Nginx & Web Deployment
---
## Commands used-
```
ssh -i "mykewy.pem" ubuntu@ec2-13-222-57-57.compute-1.amazonaws.com
sudo apt update
sudo apt install nginx

```

<img width="959" height="774" alt="image" src="https://github.com/user-attachments/assets/a841dad2-f89a-495f-a31e-26cf2827e045" />


```
cd /var/log/nginx
ls -l
sudo cat /var/log/nginx/access.log
sudo tail -f /var/log/nginx/access.log
sudo cat /var/log/nginx/error.log
sudo tail -f /var/log/nginx/error.log
sudo grep -i error /var/log/nginx/error.log
sudo grep -i "permission denied" /var/log/nginx/error.log
sudo tail -n 100 /var/log/nginx/error.log

```

<img width="935" height="481" alt="image" src="https://github.com/user-attachments/assets/15fc985d-fa26-4b62-889b-b5dfcb03288b" />

---
