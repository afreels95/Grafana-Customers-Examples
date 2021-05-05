
Hello All! 

Wanted to do a quick write up on how easy it is to start sending metrics from your windows servers to Grafana Cloud

Step 1. Install windows exporter on your server. URL: https://github.com/prometheus-community/windows_exporter/releases

Step 2. Install Prometheus on your windows server URL: https://prometheus.io/download/

Step 3: Edit the prometheus.yml file and fill in your Grafana Cloud info. 

Step 4. Run prometheus with the prometheus.yml in this repo to scrape the windows exporter endpoint. 


Check this guide for a more detailed walkthru with screenshots. https://fitdevops.in/monitoring-windows-servers-using-wmi-exporter-prometheus/

IF YOU GET STUCK CHECK WINDOWS SERVICES TO MAKE SURE EACH PART IS RUNNING.
