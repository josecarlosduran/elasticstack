<h1>ELASTIC STACK</h1>
<p align="center">ELASTIC STACK FOR DEVELOPING ENVIRONMENT</p>

I use this stack for my apps environment in dev. Now I only use for logs analysis in Kibana.
The data collector is actually Logstash. 


## Prerequisites
``` Docker```
<br>
Windows : Install from <a href ="https://docs.docker.com/docker-for-windows/install/"> here </a>
<br>
Linux :  Install from <a href="https://docs.docker.com/install/linux/docker-ce/ubuntu/"> here</a> 
<br>
Mac :  Install from <a href="https://docs.docker.com/docker-for-mac/install/"> here</a>
<br>

``` Git```
<br>
Install from <a href ="https://git-scm.com/book/en/v2/Getting-Started-Installing-Git"> here </a>
## Installation
Clone the repository with git

```
git clone
```

Modify in docker-compose.yml the second volume for logstash with your directory of logs.

Actually line 20 :
      - '../myfinance3/apps/Portal/backend/var/log:/logs'


## Usage with Docker

Just run:

```
docker-compose up -d
```

<br>

## Contributing
There are some things missing feel free to add this if you want! If you want
some guidelines feel free to contact:)

Feel free for use for your own projects.
