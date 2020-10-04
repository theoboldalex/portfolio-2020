---
title: 'Encord'
date: 2020-10-04T15:27:31+01:00
draft: false
blurb: 'A video and screen casting application based on concord.'
stack: ['Node', 'Express', 'WebRTC', 'PeerJS']
liveSite: 'https://encord-cast.ew.r.appspot.com/'
github: 'https://github.com/theoboldalex/encord'
---

## _Encord is a video chat and screen sharing application based on [condord](https://blog.usejournal.com/concord-how-i-built-a-screen-sharing-application-in-two-weeks-bef3f6a56ec4)._

Encord is built on a Node and Express backend which uses [UUID](https://www.npmjs.com/package/uuid) to generate a unique url. This route can then be used to receive a stream of either webcam video or a screen cast from the user at the home route.

The main functionality of the application is handled via [WebRTC](https://webrtc.org/) using the [PeerJS](https://peerjs.com/) library.

This application is very much still a work in progress. If you would like to contribute to the project, please submit a pull request to [the repo](https://github.com/theoboldalex/encord) or reach out to me on [twitter](https://twitter.com/theoboldalex).
