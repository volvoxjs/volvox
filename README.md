# microphone - Self announcing services
![](https://avatars3.githubusercontent.com/u/16361502?v=3&s=200)  

Microservice framework with powerful service discovery using Consul or ETCD

[![Build Status](https://travis-ci.org/microphonejs/microphone-core.svg?branch=master)](https://travis-ci.org/microphonejs/microphone-core) [![Coverage Status](https://coveralls.io/repos/github/microphonejs/microphone-core/badge.svg?branch=master)](https://coveralls.io/github/microphonejs/microphone-core?branch=master)

> Prepare your app and **Microphone.js** takes care of the rest. It starts application on available port registers application to **Consul** or **Etcd** and starts _reaper_ that polls for critical instances and deregister them. Also, **microphone.js** provides **/status** endpoint for Consul check.
![](https://raw.githubusercontent.com/microphonejs/microphone-core/master/misc/microphone-consul-fabio.png)  
