## Overview
RestBird is an easy-to-use and best programmable all-in-one Rest development tools set, include Rest debug, (auto) Test, loading, MockServer, Recording and Replay.

restbird can be deployed as a docker container, which can be on your local pc using by yourself, or on a server that  can be shared by the whole team.

restbird upports unlimited users, projects, cases, apis, scripts. All project cases support golang, JavaScript(nodejs) or Python programming, and no restriction on importing any 3rd party library. Flexible to choose what you are farmiliar with or you like.

Everything is saved on host’s local filesystem, this is the code base you can manage with any of your version control system ( git , svn , etc.)

You can also choose any of your favorite code editor to edit case, api. Every change you made is reflected in Restbird web portal instantly for better visualization and testing, isn’t it amazing?

## Install restbird

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



