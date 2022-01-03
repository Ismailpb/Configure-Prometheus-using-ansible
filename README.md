# Configure-Prometheus-using-ansible

Here we have setup Prometheus using ansible.


### OutPut

---
service prometheus status
Redirecting to /bin/systemctl status prometheus.service
 prometheus.service - Prometheus
   Loaded: loaded (/etc/systemd/system/prometheus.service; enabled; vendor preset: disabled)
   Active: active (running) since Mon 2022-01-03 20:11:48 UTC; 6min ago
 Main PID: 2310 (prometheus)
   CGroup: /system.slice/prometheus.service
           └─2310 /usr/local/bin/prometheus --config.file /opt/prometheus-2.32.1.linux-amd64/prometheus.yml --storage.tsdb.path /opt/prometh...

Jan 03 20:11:48 ip-172-31-13-40.ap-south-1.compute.internal prometheus[2310]: ts=2022-01-03T20:11:48.887Z caller=head.go:522 level=info …2.64µs
Jan 03 20:11:48 ip-172-31-13-40.ap-south-1.compute.internal prometheus[2310]: ts=2022-01-03T20:11:48.888Z caller=head.go:528 level=info ...ile"

---
