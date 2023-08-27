# scrape-kubernetes-cadvisor-from-outside-cluster
Prometheus config to scrape kubernetes cadvisor metrics from outside of the kubernetes cluster.

## what you will need

A working kubernetes cluster and prometheus set up.

A service account token. Refer to the following url if you don't have one.

https://github.com/Nirzak/service-account-to-access-kubernetes-api

## Steps

Add your service account token on `<paste_the_service_token_here>` section.

Copy sd configuration from prometheus.yml file from this repo and paste under your `scrape_configs:` section of prometheus.yml config file. 
