# Filebeat role
Install Elastic's filebeat.

Should work on macOS, Debian, Ubuntu, Centos, RHEL

## variables
```
elk_version: "7.8.0"
mac_install_location: "/Applications/Filebeat"
elastic_search_address: "127.0.0.1:9200"
configure_kibana: true
kibana_address: "127.0.0.1:5601"
ilm_enabled: true
filebeat_reload: true
filebeat_reload_period: 5m
filebeat_tags: ["default"]
filebeat_use_central_management: false
filebeat_cm_url: []
filebeat_cm_token: []
```
