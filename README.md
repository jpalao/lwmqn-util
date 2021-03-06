![LWMQN Network](https://raw.githubusercontent.com/lwmqn/documents/master/media/lwmqn_net.png)

<div align="center">

**lwmqn-util** is an utility for LWMQN mqtt-shepherd server and mqtt-node client libraries.
  
[![Greenkeeper badge](https://badges.greenkeeper.io/lwmqn/lwmqn-util.svg?style=flat-square)](https://greenkeeper.io/)
[![NPM version](https://img.shields.io/npm/v/lwmqn-util.svg?style=flat-square)](https://www.npmjs.com/package/lwmqn-util)
[![NPM downloads](https://img.shields.io/npm/dm/lwmqn-util.svg?style=flat-square)](https://www.npmjs.com/package/lwmqn-util)
[![Travis branch](https://img.shields.io/travis/lwmqn/lwmqn-util/master.svg?maxAge=2592000&style=flat-square)](https://travis-ci.org/lwmqn/lwmqn-util)
[![Coverage Status](https://coveralls.io/repos/github/lwmqn/lwmqn-util/badge.svg?branch=master&style=flat-square)](https://coveralls.io/github/lwmqn/lwmqn-util?branch=master)
[![Gitter](https://img.shields.io/gitter/room/lwmqn/Lobby.svg?style=flat-square)](https://gitter.im/lwmqn/Lobby) 
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](http://standardjs.com/)
![pr-welcoming-image](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)

</div>

-------

## What is LWMQN

Lightweight MQTT machine network ([**LWMQN**](http://lwmqn.github.io)) is an open source project that follows part of [**OMA LWM2M v1.0**](http://technical.openmobilealliance.org/Technical/technical-information/release-program/current-releases/oma-lightweightm2m-v1-0) specification to meet the minimum requirements of machine network management.  

### Server-side and Client-side Libraries:
   - LWMQN project provides you with this machine-side **mqtt-node** library and a server-side [**mqtt-shepherd**](https://github.com/lwmqn/mqtt-shepherd) library to build your machine network with JavaScript and node.js easily. 

* Server-side library: [**mqtt-shepherd**](https://github.com/lwmqn/mqtt-shepherd)
* Client-side library: [**mqtt-node**](https://github.com/lwmqn/mqtt-node)
* [**A simple demo webapp**](https://github.com/lwmqn/lwmqn-demo)

**lwmqn-util** is a utility for Lightweight Mqtt Machine Network Server([mqtt-shepherd](https://github.com/lwmqn/mqtt-shepherd)) and Client([mqtt-node](https://github.com/lwmqn/mqtt-node))  modules. This utility provides some common methods of getting identifiers in string or in number, getting command ids, getting response codes, and tackling the path of resource alloaction.

-------

## Installation

Currently [Node.js 8.x LTS](https://nodejs.org/en/about/releases/) or higher is required.

```bash
$ npm install lwmqn-util
```

-------

## Documentation

Please visit the <a href="https://github.com/lwmqn/lwmqn-util/blob/master/docs/API.md"><code><b>API</b></code></a>.

-------

## License

Licensed under [MIT](https://github.com/lwmqn/lwmqn-util/blob/master/LICENSE).
