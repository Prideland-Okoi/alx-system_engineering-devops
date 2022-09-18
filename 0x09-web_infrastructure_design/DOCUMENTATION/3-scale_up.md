# Scale up Web Infrastructure

[![a-3-scale-up.png](https://i.postimg.cc/SK3S4g3x/a-3-scale-up.png)](https://postimg.cc/Jy3Vc5Rf)

## Description

  Added a load balancer configured as a cluster with the previous one(See 2-secured_and_monitored_web_infrastructure).

## Specifics About This Infrastructure

  This infrastructure basically breaks down each component in each server to independent unit. Which eliminates a single point of failure, as the load balancers can direct traffic accordingly without the need for a downtime. Also, maintenance actions can occur without any downtime on the website. Overall, there is added security on all layers and levels of the internal network and external traffic. With monitoring, more data collection points and metrics are available to the admin, which will also help to improve and maintain network performance, along with zero downtime.
