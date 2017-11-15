# grafana_dashboards

InfluxDB receives traffic reports from FastNetMon collectors and Grafana plots nice graphs with it.

Requirements:

- FastNetMon by Pavel Odintsov - https://github.com/pavel-odintsov/fastnetmon configured with InfluxDB (https://github.com/FastVPSEestiOu/fastnetmon/blob/master/docs/INFLUXDB_INTEGRATION.md)
- Grafana (https://github.com/grafana/grafana)

###### Main Dashboard

https://grafana.com/dashboards/2216

![alt text](https://github.com/openbsod/grafana_dashboards/blob/master/images/main.png)

###### Main Dashboard Fastnetmon Advanced ClickHouse

https://grafana.com/dashboards/3413

![alt text](https://github.com/openbsod/grafana_dashboards/blob/master/images/fnm-adv-ch.png)

###### Top hosts Dashboard

https://grafana.com/dashboards/2225

![alt text](https://github.com/openbsod/grafana_dashboards/blob/master/images/top_hosts.png)

###### Top networks Dashboard

https://grafana.com/dashboards/2228

![alt text](https://github.com/openbsod/grafana_dashboards/blob/master/images/top-networks.png)

###### Top outgoing Dashboard

https://grafana.com/dashboards/2234

![alt text](https://github.com/openbsod/grafana_dashboards/blob/master/images/top-outgoing-hosts-fnm-community.png)

###### Traffic for single specified /32 host Dashboard

https://grafana.com/dashboards/2237

![alt text](https://github.com/openbsod/grafana_dashboards/blob/master/images/traffic_for_host.png)

###### Traffic for single specified network Dashboard

https://grafana.com/dashboards/2243

![alt text](https://github.com/openbsod/grafana_dashboards/blob/master/images/traffic_for_network.png)

###### Direct stream sFlow\Netflow data to InfluxDB 

After all you may want collect your entyre sFlow/Netflow data directly to ClickHouse or InfluxDB

![alt text](https://github.com/openbsod/grafana_dashboards/blob/master/images/influx.png)










