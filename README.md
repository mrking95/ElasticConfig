# ELK Config
Elastic Logstash Kibana configuration


# Beats Config
Filebeat, Metricbeat, Auditbeat and Winlogbeat configuration

Upload files via FTP
run
```
cd ~
sudo cp -R metricbeat/* /etc/metricbeat/
sudo cp -R filebeat/* /etc/filebeat/
sudo cp -R auditbeat/* /etc/auditbeat/
sudo systemctl restart metricbeat
sudo systemctl restart filebeat
sudo systemctl restart auditbeat
```

## Filebeat
https://artifacts.elastic.co/downloads/beats/filebeat/filebeat-6.2.3-x86_64.zip
```
yum -y install https://artifacts.elastic.co/downloads/beats/filebeat/filebeat-6.2.3-x86_64.rpm
systemctl enable filebeat
```

Download config & change values

```
systemctl start filebeat
```

## Metricbeat
https://artifacts.elastic.co/downloads/beats/filebeat/metricbeat-6.2.3-x86_64.zip
```
yum -y install https://artifacts.elastic.co/downloads/beats/filebeat/metricbeat-6.2.3-x86_64.rpm
systemctl enable filebeat
```

Download config & change values

```
systemctl start filebeat
```

## Auditbeat
https://artifacts.elastic.co/downloads/beats/filebeat/auditbeat-6.2.3-x86_64.zip
```
yum -y install https://artifacts.elastic.co/downloads/beats/filebeat/auditbeat-6.2.3-x86_64.rpm
systemctl enable filebeat
```

Download config & change values

```
systemctl start filebeat
```

## Winlogbeat
https://artifacts.elastic.co/downloads/beats/winlogbeat/winlogbeat-6.2.3-windows-x86_64.zip
