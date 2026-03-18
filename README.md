<div align="center">

<!-- ██ SELF-HOSTED SVG BANNER — served from raw.githubusercontent.com — ALWAYS RENDERS ██ -->
<img src="https://raw.githubusercontent.com/Narenrohitha/wordpress-5server-infrastructure/main/assets/banner.svg" width="100%" alt="Banner"/>

<br/><br/>

<!-- ██ SHIELDS.IO BADGES ROW 1 — 100% reliable ██ -->
<img src="https://img.shields.io/badge/Nginx-Load_Balancer-009639?style=for-the-badge&logo=nginx&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/WordPress-2×_Nodes-21759B?style=for-the-badge&logo=wordpress&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/MySQL-8.x_Isolated-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Ubuntu-24.04_LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white&labelColor=0d1117"/>

<br/>

<img src="https://img.shields.io/badge/Elasticsearch-8.x-005571?style=for-the-badge&logo=elasticsearch&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Kibana-Dashboards-E8478B?style=for-the-badge&logo=kibana&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Prometheus-Monitoring-E6522C?style=for-the-badge&logo=prometheus&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Grafana-Visualization-F46800?style=for-the-badge&logo=grafana&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/WooCommerce-E--Commerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white&labelColor=0d1117"/>

<br/><br/>

<!-- ██ SELF-HOSTED STATS SVG ██ -->
<img src="https://raw.githubusercontent.com/Narenrohitha/wordpress-5server-infrastructure/main/assets/stats.svg" width="100%" alt="Live Stats"/>

<br/><br/>

<!-- ██ SOCIAL LINKS ██ -->
<a href="https://medium.com/@narengl2001">
<img src="https://img.shields.io/badge/📖_Full_Blog_on_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/>
</a>
<a href="https://github.com/Narenrohitha">
<img src="https://img.shields.io/badge/GitHub-Narenrohitha-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>
<a href="https://www.linkedin.com/in/naren-g-7bb580229/">
<img src="https://img.shields.io/badge/LinkedIn-Naren_G-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

<img src="https://img.shields.io/github/stars/Narenrohitha/wordpress-5server-infrastructure?style=for-the-badge&logo=github&color=fbbf24&labelColor=0d1117&label=⭐+Stars"/>
<img src="https://img.shields.io/github/forks/Narenrohitha/wordpress-5server-infrastructure?style=for-the-badge&logo=github&color=a78bfa&labelColor=0d1117&label=Forks"/>
<img src="https://komarev.com/ghpvc/?username=Narenrohitha-wp5&label=👁️+Views&color=0ea5e9&style=for-the-badge"/>

</div>

---

<div align="center">

## 🏗️ Architecture

<!-- ██ SELF-HOSTED ARCHITECTURE SVG ██ -->
<img src="https://raw.githubusercontent.com/Narenrohitha/wordpress-5server-infrastructure/main/assets/architecture.svg" width="100%" alt="Architecture"/>

</div>

---

<div align="center">

## 🖥️ Server Roles

| Server | Role | Stack | Access |
|:---:|:---:|:---:|:---:|
| ![](https://img.shields.io/badge/LB-Nginx-009639?style=flat-square&logo=nginx&logoColor=white) | **Load Balancer** | Nginx Round-Robin + vHosts | `:80` |
| ![](https://img.shields.io/badge/Web_1-WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white) | **WordPress Node 1** | Apache · PHP 8.3 · WooCommerce | `:30080` |
| ![](https://img.shields.io/badge/Web_2-WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white) | **WordPress Node 2** | Apache · PHP 8.3 · WooCommerce | `:30080` |
| ![](https://img.shields.io/badge/DB-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | **MySQL Database** | MySQL 8.x · Remote-Only | `3306` |
| ![](https://img.shields.io/badge/ELK-Monitoring-005571?style=flat-square&logo=elasticsearch&logoColor=white) | **Full Monitoring** | ELK · Prometheus · Grafana | `5601` `9090` `3000` |

</div>

---

<div align="center">

## 🛠️ Tech Stack

<!-- ██ SKILLICONS — works via GitHub's Camo proxy ██ -->
<img src="https://skillicons.dev/icons?i=nginx,mysql,linux,bash,elasticsearch,grafana&theme=dark&perline=6"/>
<br/>
<img src="https://skillicons.dev/icons?i=prometheus,docker,git,github,python,vscode&theme=dark&perline=6"/>

<br/><br/>

![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.3-777BB4?style=flat-square&logo=php&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-E8478B?style=flat-square&logo=kibana&logoColor=white)
![Logstash](https://img.shields.io/badge/Logstash-005571?style=flat-square&logo=logstash&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Filebeat](https://img.shields.io/badge/Filebeat-00BFB3?style=flat-square&logo=elastic&logoColor=white)
![Metricbeat](https://img.shields.io/badge/Metricbeat-EE4B9D?style=flat-square&logo=elastic&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![UFW](https://img.shields.io/badge/UFW-Firewall-ef4444?style=flat-square)

</div>

---

<div align="center">
<img src="https://img.shields.io/badge/━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-PART_1:_MySQL_Database_Server━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</div>

### `STEP 01` — Install & Secure MySQL
> 🎯 ![](https://img.shields.io/badge/DB_SERVER_ONLY-4479A1?style=flat-square&logo=mysql&logoColor=white)

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install mysql-server -y
sudo systemctl start mysql && sudo systemctl enable mysql
sudo mysql_secure_installation
```

### `STEP 02` — Create Databases & Remote Users

```sql
sudo mysql -u root -p

CREATE DATABASE woocommerce_db  CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
CREATE DATABASE woocommerce_db3 CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;

CREATE USER 'woo_user'@'[WEB1_IP]'  IDENTIFIED BY 'StrongPassword123!';
CREATE USER 'woo_user3'@'[WEB2_IP]' IDENTIFIED BY 'StrongPassword123!';
GRANT ALL PRIVILEGES ON woocommerce_db.*  TO 'woo_user'@'[WEB1_IP]';
GRANT ALL PRIVILEGES ON woocommerce_db3.* TO 'woo_user3'@'[WEB2_IP]';
FLUSH PRIVILEGES;
```

> ⚠️ ![](https://img.shields.io/badge/%231_Mistake-DB_NAME_mismatch-red?style=flat-square) `DB_NAME` in GRANT **must exactly match** `wp-config.php` — or WordPress fails silently.

### `STEP 03` — Remote Access + Slow Query Logging

```ini
# /etc/mysql/mysql.conf.d/mysqld.cnf
bind-address        = 0.0.0.0
slow_query_log      = 1
slow_query_log_file = /var/log/mysql/mysql-slow.log
long_query_time     = 2
```

### `STEP 04` — Firewall

```bash
sudo ufw allow from [WEB1_IP] to any port 3306
sudo ufw allow from [WEB2_IP] to any port 3306
sudo ufw allow from [ELK_IP]  to any port 9100
sudo ufw enable && sudo systemctl restart mysql
```

> 💡 Test before touching WordPress: `mysql -u woo_user -p -h [DB_IP] woocommerce_db -e "SELECT 1;"`

---

<div align="center">
<img src="https://img.shields.io/badge/━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-PART_2:_WordPress_Web_Servers━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-21759B?style=for-the-badge&logo=wordpress&logoColor=white"/>
</div>

### `STEP 05` — Install LAMP Stack
> 🔁 ![](https://img.shields.io/badge/BOTH_WEB_SERVERS-21759B?style=flat-square&logo=wordpress&logoColor=white)

```bash
sudo apt install apache2 php8.3 php8.3-mysql php8.3-curl php8.3-gd \
  php8.3-mbstring php8.3-xml php8.3-zip mysql-client -y
sudo a2enmod rewrite && sudo systemctl restart apache2
```

### `STEP 06` — Install WordPress

```bash
cd /var/www/html && sudo rm -f index.html
sudo wget https://wordpress.org/latest.tar.gz
sudo tar -xzf latest.tar.gz && sudo mv wordpress/* .
sudo chown -R www-data:www-data /var/www/html
```

### `STEP 07` — wp-config.php

```php
// Web Server 1
define( 'DB_NAME',     'woocommerce_db' );
define( 'DB_USER',     'woo_user' );
define( 'DB_PASSWORD', 'StrongPassword123!' );
define( 'DB_HOST',     '[DB_IP]' );   // NOT localhost!
define( 'WP_HOME',     'http://site1.com' );
define( 'WP_SITEURL',  'http://site1.com' );
// Web Server 2: DB_NAME=woocommerce_db3, DB_USER=woo_user3, WP_HOME=site2.com
```

---

<div align="center">
<img src="https://img.shields.io/badge/━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-PART_3:_Nginx_Load_Balancer━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
</div>

### `STEP 08` — Round-Robin + Domain Routing

```nginx
upstream wordpress_backend {
    server [WEB1_IP]:80;
    server [WEB2_IP]:80;
    keepalive 32;
}
server {
    listen 80;
    server_name [LB_IP];
    location / {
        proxy_pass http://wordpress_backend;
        proxy_set_header Host            $host;
        proxy_set_header X-Real-IP       $remote_addr;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
    }
}
# Prometheus metrics endpoint
server {
    listen 127.0.0.1:8080;
    location /nginx_status { stub_status on; allow 127.0.0.1; deny all; }
}
```

```bash
sudo nginx -t && sudo systemctl reload nginx
```

---

<div align="center">
<img src="https://img.shields.io/badge/━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-PART_4:_ELK_Stack━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"/>
</div>

### `STEP 09` — Install Elasticsearch + Kibana + Logstash

```bash
sudo apt install openjdk-21-jdk -y
wget -qO - https://artifacts.elastic.co/GPG-KEY-elasticsearch | \
  sudo gpg --dearmor -o /usr/share/keyrings/elasticsearch-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/elasticsearch-keyring.gpg] \
  https://artifacts.elastic.co/packages/8.x/apt stable main" | \
  sudo tee /etc/apt/sources.list.d/elastic-8.x.list
sudo apt update
sudo apt install elasticsearch kibana logstash -y
```

### `STEP 10` — Elasticsearch Config

```yaml
# /etc/elasticsearch/elasticsearch.yml
cluster.name: my-elk-cluster
network.host: 0.0.0.0
discovery.type: single-node
xpack.security.enabled: true
xpack.security.http.ssl.enabled: false
```

### `STEP 11` — Logstash Pipeline

```ruby
input { beats { port => 5044 } }
filter {
  if [log_type] == "nginx_lb" {
    grok  { match => { "message" => "%{COMBINEDAPACHELOG}" } }
    geoip { source => "clientip" }
  }
}
output {
  elasticsearch {
    hosts => ["http://localhost:9200"]
    user  => "elastic"
    password => "YourPassword"
    index => "%{[log_type]}-%{+yyyy.MM.dd}"
  }
}
```

---

<div align="center">
<img src="https://img.shields.io/badge/━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-PART_5:_Filebeat_+_Metricbeat━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-00BFB3?style=for-the-badge&logo=elastic&logoColor=white"/>
</div>

### `STEP 12` — Install on All 4 Servers
> 🔁 ![](https://img.shields.io/badge/LB_+_WEB1_+_WEB2_+_DB-00BFB3?style=flat-square)

```bash
sudo apt install filebeat metricbeat -y

# Test before enabling
sudo filebeat test config && sudo filebeat test output
sudo systemctl enable --now filebeat metricbeat
```

**Filebeat fields per server** — tag every log with source info:

```yaml
fields:
  log_type:    "nginx_lb"        # nginx_access / apache / mysql_error / mysql_slowquery
  server_role: "load_balancer"   # web_server / database
  server_ip:   "[THIS_SERVER_IP]"
fields_under_root: true

output.elasticsearch:
  hosts: ["https://[ELK_IP]:9200"]
  username: "elastic"
  password: "YourPassword"
  ssl.verification_mode: none
setup.ilm.enabled: false
setup.template.enabled: false
```

---

<div align="center">
<img src="https://img.shields.io/badge/━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-PART_6:_Prometheus_+_Grafana━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
</div>

### `STEP 13` — Node Exporter on ALL Servers

```bash
cd /tmp
wget https://github.com/prometheus/node_exporter/releases/download/v1.7.0/node_exporter-1.7.0.linux-amd64.tar.gz
tar xvf node_exporter-*.tar.gz
sudo mv node_exporter-*/node_exporter /usr/local/bin/
sudo useradd -rs /bin/false node_exporter
sudo systemctl enable --now node_exporter
sudo ufw allow from [ELK_IP] to any port 9100
```

### `STEP 14` — Prometheus Scrape Config

```yaml
global:
  scrape_interval: 15s
scrape_configs:
  - job_name: "lb-server"
    static_configs:
      - targets: ["[LB_IP]:9100"]
        labels: { server_role: "load_balancer" }
  - job_name: "web-server-1"
    static_configs:
      - targets: ["[WEB1_IP]:9100"]
        labels: { server_role: "web" }
  - job_name: "web-server-2"
    static_configs:
      - targets: ["[WEB2_IP]:9100"]
        labels: { server_role: "web" }
  - job_name: "db-server"
    static_configs:
      - targets: ["[DB_IP]:9100"]
        labels: { server_role: "database" }
  - job_name: "mysql"
    static_configs:
      - targets: ["[DB_IP]:9104"]
        labels: { server_role: "database", service: "mysql" }
rule_files: ["alerts.yml"]
```

### `STEP 15` — Import Grafana Dashboards

```bash
sudo apt install grafana -y && sudo systemctl enable --now grafana-server
# http://[ELK_IP]:3000  →  admin/admin
```

<div align="center">

| Dashboard ID | Name | Shows |
|:---:|:---:|:---|
| `1860` | **Node Exporter Full** | CPU · Memory · Disk · Network per server |
| `7362` | **MySQL Overview** | Queries · Connections · Slow log |
| `405` | **Server Overview** | Cross-server health summary |

</div>

### `STEP 16` — Alert Rules

```yaml
groups:
  - name: server_alerts
    rules:
      - alert: InstanceDown
        expr: up == 0
        for: 2m
        labels: { severity: critical }
        annotations:
          summary: "🔴 Instance {{ $labels.instance }} is DOWN"
      - alert: HighCPU
        expr: 100-(avg by(instance)(rate(node_cpu_seconds_total{mode="idle"}[5m]))*100) > 80
        for: 5m
        labels: { severity: warning }
      - alert: HighMemory
        expr: (node_memory_MemTotal_bytes-node_memory_MemAvailable_bytes)/node_memory_MemTotal_bytes*100 > 85
        for: 5m
        labels: { severity: warning }
```

---

<div align="center">

## 🩺 Troubleshooting

</div>

<details>
<summary><b>🔴 &nbsp;"Error establishing a database connection"</b> &nbsp;<img src="https://img.shields.io/badge/Fix-DB_NAME_mismatch-red?style=flat-square"/></summary><br>

```bash
# DB_NAME in GRANT must EXACTLY match wp-config.php
mysql -u woo_user -p -h [DB_IP] woocommerce_db -e "SELECT 1;"
# Fix any error here before touching WordPress
```
</details>

<details>
<summary><b>🟠 &nbsp;Elasticsearch won't start</b> &nbsp;<img src="https://img.shields.io/badge/Fix-vm.max__map__count-orange?style=flat-square"/></summary><br>

```bash
sudo sysctl -w vm.max_map_count=262144
echo "vm.max_map_count=262144" | sudo tee -a /etc/sysctl.conf
sudo systemctl restart elasticsearch
```
</details>

<details>
<summary><b>🟡 &nbsp;Filebeat not shipping logs</b> &nbsp;<img src="https://img.shields.io/badge/Fix-Test_output-yellow?style=flat-square"/></summary><br>

```bash
sudo filebeat test config && sudo filebeat test output
sudo journalctl -u filebeat -f
```
</details>

<details>
<summary><b>🔵 &nbsp;Prometheus target DOWN</b> &nbsp;<img src="https://img.shields.io/badge/Fix-UFW_port_9100-blue?style=flat-square"/></summary><br>

```bash
sudo ufw allow from [ELK_IP] to any port 9100
curl http://[SERVER]:9100/metrics
```
</details>

<details>
<summary><b>⚫ &nbsp;MySQL remote connection refused</b> &nbsp;<img src="https://img.shields.io/badge/Fix-bind--address-black?style=flat-square"/></summary><br>

```bash
grep bind-address /etc/mysql/mysql.conf.d/mysqld.cnf
# Must be: bind-address = 0.0.0.0
sudo systemctl restart mysql
```
</details>

---

<div align="center">

## ✅ Final State

```
╔══════════════════════════════════════════════════════════════════════╗
║              INFRASTRUCTURE — FULLY OPERATIONAL                     ║
╠══════════════════════════════════════════════════════════════════════╣
║  🔀  Nginx LB        Running  ████████████████████  Round-Robin ✅  ║
║  🔷  WordPress 1     Running  ████████████████████  WooCommerce ✅  ║
║  🔷  WordPress 2     Running  ████████████████████  WooCommerce ✅  ║
║  🗄️  MySQL DB        Running  ████████████████████  Remote-Only ✅  ║
║  📊  Kibana          Live     ████████████████████  1,185 events 🔥 ║
║  🔥  Prometheus      Scraping ████████████████████  5/5 UP ✅       ║
║  📈  Grafana         Live     ████████████████████  Dashboards ✅   ║
║  🟢  Network Errors  Zero     ████████████████████  0 errors ✅     ║
╚══════════════════════════════════════════════════════════════════════╝
```

## 📚 More by Naren

| Article | Tags |
|:---|:---:|
| [**🚀 WordPress 5-Server Infra**](https://medium.com/@narengl2001) — *this guide* | ![](https://img.shields.io/badge/-Nginx-009639?style=flat-square) ![](https://img.shields.io/badge/-ELK-005571?style=flat-square) |
| [**☸️ Kubernetes + ELK Stack**](https://medium.com/@narengl2001) | ![](https://img.shields.io/badge/-K8s-326CE5?style=flat-square) ![](https://img.shields.io/badge/-Helm-0F1689?style=flat-square) |
| [**🔧 Pod Troubleshooting Guide**](https://medium.com/@narengl2001) | ![](https://img.shields.io/badge/-Debug-ef4444?style=flat-square) |
| [**📋 50 K8s Interview Questions**](https://medium.com/@narengl2001) | ![](https://img.shields.io/badge/-Interview-fbbf24?style=flat-square) |

<br/>

[![Medium](https://img.shields.io/badge/Follow_on_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@narengl2001)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naren-g-7bb580229/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Narenrohitha)

<br/>

*⭐ Star this repo if it saved you hours of debugging!*

</div>
