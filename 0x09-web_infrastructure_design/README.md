# Web infrastructure design

Project done during **ALX Stack Software Scholarship 2022** at **Alx Students Education**. It aims to learn about how to design a Web Infrastructure.

<img src="https://www.nginx.com/wp-content/uploads/2014/07/what-is-load-balancing-diagram-NGINX.png" width="600px"/>


## Resources

Read or watch:

* [Network basics concept page](https://www.computernetworkingnotes.com/networking-tutorials/networking-basic-concepts-and-fundamentals-explained.html)
* [Server concept page](https://www.paessler.com/server_monitoring_software#server-definition)
* [Web server concept page](https://www.paessler.com/server_monitoring_software#server-definition)
* [DNS concept page](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
* [Load balancer concept page](https://www.nginx.com/resources/glossary/load-balancing/)
* [Monitoring concept page](https://www.ibm.com/docs/en/ftmswsfm300?topic=components-monitoring-concepts)
* [What is a database](https://www.techtarget.com/searchdatamanagement/definition/database)
* [What’s the difference between a web server and an app server?](https://www.youtube.com/watch?v=S97eKyv2b9M)
* [DNS record types](https://pressable.com/?s=DNS&post_type=knowledgebase)
* [Single point of failure](https://en.wikipedia.org/wiki/Single_point_of_failure)
* [How to avoid downtime when deploying new code](https://softwareengineering.stackexchange.com/questions/35063/how-do-you-update-your-production-codebase-database-schema-without-causing-downt#answers-header)
* [High availability cluster (active-active/active-passive)](https://docs.oracle.com/cd/E17904_01/core.1111/e10106/intro.htm#ASHIA712)
* [What is HTTPS](https://www.instantssl.com/http-vs-https)
* [What is a firewall](https://www.webopedia.com/definitions/firewall/)

<img src="https://dksignmt.com/wp-content/uploads/2015/04/servidor-lamp.jpg" width="400px"/>

## Technologies
[Mural](app.mural.co)
[Postimage](i.postimg.cc)

## Files

| Filename | Description |
| -------- | ----------- |
| `0-simple_web_stack` | Web Infrastructure Design with a LAMP stack. This contains: 1 server, 1 web server, 1 application server, 1 database and 1 domain name |
| `1-distributed_web_infrastructure` | Web Infrastructure Design, based on `0-simple_web_stack` that contains some additional components: 1 server, 1 web server, 1 application server, 1 load-balancer, 1 set of application files, 1 database |
| `2-secured_and_monitored_web_infrastructure` | Web Infrastructure Design, based on `1-distributed_web_infrastructure` that contains some additional components: 3 firewalls, 1 SSL certificate, 3 monitoring clients |
| `3-scale_up` | Web Infrastructure Design, based on `2-secured_and_monitored_web_infrastructure` that contains some additional components: 1 server, 1 load-balancer |
