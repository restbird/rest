## Overview
RestBird is an easy-to-use and best programmable all-in-one Rest development tools set, include Rest debug, (auto) Test, loading, MockServer, Recording and Replay.

restbird can be deployed as a docker container, which can be on your local pc using by yourself, or on a server that  can be shared by the te

Docker delopyment, support team collaboration by nature.
Supports unlimited users, projects, cases, apis, scripts. 

#### Step1 : Pull RestBird docker image

```bash
$ sudo docker pull restbird/rest
```

#### Step2: Creat Project Directory on host for Restbird/rest Container

The project directory can be any place,  take '/var/my-first-project' for example:
```bash
$mkdir /var/my-first-project
$ls /var/my-first-project
```

#### Step3:  run the restbird/rest container and mapping the project directory we just created.
```bash
sudo docker run    -ti    -p 8080:8080    -v /var/my-first-project:/data/restbird    restbird/rest
```

Now, we can launch the browser to access the restbird portal: http://localost:8080/ or http://{host-ip-address}:8080/  

![RestBird Login](https://restbird.org/static/restbird-login-9bd8e545ae189a0efb1469f080cad97d-9794d.png)

The default username and password is ***admin***/***admin***. Once login, here is the dashboard:

![RestBird dashboard](https://restbird.org/static/restbird-dashboard-1ba9d4684496e0107fde9abc639452f8-ee8d1.png)

here is the rest testing:
![RestBird rest](https://restbird.org/static/dash-rest.c1580d3a.gif)



