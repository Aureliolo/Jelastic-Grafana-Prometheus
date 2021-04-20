# Grafana JPS to install Enterprise or OSS Edition

When you launch the JPS you have 3 Options; the version of Grafana, if you want a public IP + Let's Encrypt as well as if you want to install Prometheus

On the version tab you can select between Enterprise and OSS Edition, see:
https://grafana.com/blog/2019/09/04/how-we-differentiate-grafana-enterprise-from-open-source-grafana/

You also have the option to install a public IP + let's encrypt for use with your own Domain.
If you don't select this option, it will enable Platform SSL and you wil have to use the jelastic Environment URL.

If activated Prometheus will also be installed and usable.
The admin panel will be secured with basic auth from NGINX using .htpasswd

# Installation
Simply import this link using the Jelastic JPS Import function:
```
https://raw.githubusercontent.com/panslothda/Jelastic-Grafana-Prometheus/main/main.jps
```

Or copy the content of main.jps into the import window.


![Interface](images/interface.png?raw=true)


![Update Addons](images/update.png?raw=true)