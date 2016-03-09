# Trading Office - Api Gateway
[![Build Status](https://travis-ci.org/spolnik/trading-office-api-gateway.svg?branch=master)](https://travis-ci.org/spolnik/trading-office-api-gateway) [![codecov.io](https://codecov.io/github/spolnik/trading-office-api-gateway/coverage.svg?branch=master)](https://codecov.io/github/spolnik/trading-office-api-gateway?branch=master) [![Sonar Coverage](https://img.shields.io/sonar/https/sonar-nprogramming.rhcloud.com/trading-office-api-gateway/coverage.svg)](https://sonar-nprogramming.rhcloud.com/dashboard/index/1) [![Sonar Tech Debt](https://img.shields.io/sonar/https/sonar-nprogramming.rhcloud.com/trading-office-api-gateway/tech_debt.svg)](https://sonar-nprogramming.rhcloud.com/dashboard/index/1)

Trading Office is reference implementation of microservices architecture, based on Spring Boot. It's modeling part of post trade processing, mainly focused on receiving Fixml message and preparing confirmation for it.

- [Trading Office](#trading-office)
- [Api Gateway](#api-gateway)
- [Notes](#notes)

## Trading Office

- [Trading Office](https://github.com/spolnik/trading-office)

## Api Gateway
- spring boot web application
- using Netlix Zuul

Heroku: http://api-gateway.herokuapp.com/swagger-ui.html

![Component Diagram](https://raw.githubusercontent.com/spolnik/trading-office-api-gateway/master/design/api_gateway.png)

## Notes
- checking if [dependencies are up to date](https://www.versioneye.com/user/projects/56ad39427e03c7003ba41427)