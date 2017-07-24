---
layout: post
title: P2P protocols for the distributed web
date: 2013-07-06
---

If we want a distributed web, and we do, then we need distributed media sharing
services.

Tent, the distributed social network protocol, is focused on posts; JSON
metadata with file attachments. This is great for sharing text posts with a
couple hundred or thousand friends, but if you want to share media, as people
often do, you’ll need a more powerful server. This is only because the poster’s
server is responsible for serving the post to everyone.

I dream of a distributed web where people are encouraged to host their own
nodes. A distributed protocol is nice, but if the result is a few major hosts
each serving millions of users, that’s not orders of magnitude better than the
situation today. But if people are to host their own nodes, running a server
needs to be cheap. A good number of people are likely to host their own node if
it’s easy to set up and costs no more than a raspberry pi and 250GB HDD.

A server like this is certainly capable of sharing images with 1000 friends, and
probably even short videos, but what if someone shares an image publicly? What
if that image goes viral? A measly home internet connection simply isn’t capable
of handling that much activity.

What is needed is a p2p protocol for sharing media. Bittorrent is great and
would work well for generic file sharing, such as a photo album, but it is not
efficient for sharing single images. Bittorrent also isn’t good for audio and
video because people don’t want to wait for the whole file to download before
viewing it. Instead, there needs to be a specialized p2p protocol for small
files and for streaming. Maybe these already exist but are in limited use, or
maybe they need to be built from scratch. In any case, I believe that it is
possible for small, personal node to handle the workload of today’s centralized
servers.
