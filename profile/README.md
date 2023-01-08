# aqapi

## important links

webapp: [aqapi.cloud](http://aqapi.cloud)

api: [api.aqapi.cloud](http://api.aqapi.cloud)

source code: [github.com/aqapi](https://github.com/aqapi)

## about

aqapi is a free, public and open source air quality service consisting of:

- air quality api based on government-managed measurement infrastructure
- website presenting the recent data

## repos

- [api](https://github.com/aqapi/api)
    
    *the api* with a publicly released container image, based on spring framework
    
- [webapp](https://github.com/aqapi/webapp)
    
    react-based modern frontend presenting the usage of the api
    
- [iac](https://github.com/aqapi/iac)
    
    infrastructure-as-code terraform repository holding all of aws configurations, making use of terraform cloud
    
- [writer-service](https://github.com/aqapi/writer-service)
    
    serverless scheduled aws ecs task collecting the data from GIOS measurement stations, more about the project: [powietrze.gios.gov.pl](https://powietrze.gios.gov.pl/pjp/content/api)
    

## authors

- Jakub Kozubek
- Marceli Koćwin
- Wojciech Kopański

## attribution

### the icon

> <img src="/profile/dashing-away-twemoji-14-0.png" width="40" height="40">
>
> Copyright 2019 Twitter, Inc and other contributors <br>
> Graphics licensed under CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/
