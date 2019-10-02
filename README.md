Ansible role: nginx-vts-exporter
=========

This role installs [Nginx VTS Exporter](https://github.com/hnlq715/nginx-vts-exporter)


Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows. (For all variables, take a look at defaults/main.yml)

```
# The Nginx VTS Exporter version to install
nginx_vts_exporter_version: 0.10.3

# Url for scraping stats data
nginx_vts_exporter_status_url: http://localhost/status/format/json

# Metrics namespace
nginx_vts_exporter_metrics_namespace: nginx

# Binding port for exporter
nginx_vts_exporter_metrics_addr: ":9913"

# User and group to run the exporter
nginx_vts_exporter_system_user: nginx
nginx_vts_exporter_system_group: nginx
```

