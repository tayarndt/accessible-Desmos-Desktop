# Accessible Desmos Desktop

## introduction
This application is a fork of DingShizhe's desmos desktop app[https://github.com/DingShizhe/Desmos-Desktop]. I made this bersion to be accessible for people who use assistive technology. This version is based on the desmos website [https://www.desmos.com/].

## credits
The main base of this application was taken from DingShizhe's desmos desktop app[https://github.com/DingShizhe/Desmos-Desktop]. I also used the desmos api [https://www.desmos.com/api/]. Desmos is a web calculater written in javascript that can be used for graphing, scientific operations, and basic arithmitic. This app supports all the math operations that the desmos website supports.

## Build from source
If you want to help with project by contributing code, it is most likely you will need to build the application from source. Below, you will find the instructions to build desmos from source.
```
git clone [https://github.com/tayarndt/accessible-Desmos-Desktop.git]
npm install -d
npm run dist
run application
```
On linux, you need edit ./res/appimagekit-desmos.desktop properly and move it to ./local/share/applications.

## Dependency
- [Node.js](https://nodejs.org/en/)
- [Electron](http://electron.atom.io/)
- [Desmos API](https://www.desmos.com/api/)

## features
- use scientific calculator
- save desmos graphs to computer for later use
- fully accessible with screen readers
- audio tracing mode for auditory representation of graphs
- can be used by all not just blind users
- import graphs from other users
- able to find important points on graphs
- works when you are offline


