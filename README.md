# Datadog Monitoring Apache Log on Ubuntu
This guide explains how to install the Datadog Agent on an Ubuntu server, configure Apache log monitoring, and visualize metrics and logs in Datadog.

---

## Prerequisites

* Ubuntu server with Apache installed
* Datadog account and API key
* `sudo` privileges on the server

---
## EC2 
### `script` apache install
~~~sh
#!/bin/bash
apt update -y
apt install apache2 -y
systemctl start apache2
systemctl enable apache2
~~~
