---
title: "Resume"
date: 2022-07-17T00:27:34-04:00
draft: false
---

{{<row>}}

{{<item>}}
# [Jonathan Alonso](https://github.com/thatpix3l)

*Junior Software Developer*
{{</item>}}

{{<item>}}
{{<rawhtml>}}
<div style="text-align: right;">
{{</rawhtml>}}

(407)-476-5342

contact@mralonso.com

{{<rawhtml>}}
</div>
{{</rawhtml>}}
{{</item>}}

{{</row>}}

---

## Technical Skills

{{<row>}}

{{<item>}}
**Programming & Technologies**:
{{</item>}}

{{<item>}}
Go, HTML, CSS, Javascript, TypeScript, Java, Svelte, SolidJS, Bash/Linux Shell, PowerShell, Docker, Podman 
{{</item>}}

{{</row>}}

{{<rawhtml>}}
</br>
{{</rawhtml>}}

{{<row>}}

{{<item>}}
**Software & Tools**:
{{</item>}}

{{<item>}}
Git, SSH, VSCode, IntelliJ, Markdown, Vim
{{</item>}}

{{</row>}}

## Experience
**Projects**:

[Function Two](https://github.com/thatpix3l/fntwo):

Real-time 3D virtual avatar puppeteering program. Frontend written in TypeScript, Bootstrap and SolidJS. Backend WebSocket and RESTful API server written in Go. Reads live head tracking data from specific phone apps and anything else that sends data through the VirtualMotionCapture protocol, based off of OpenSoundControl, which internally uses UDP.

[PicoPear](https://github.com/thatpix3l/picopear):

Real-time livestream chat presenter, supporting "YouTube" and "Twitch". Frontend written in JavaScript and Svelte. Backend WebSocket and RESTful API server written in Go. Listens on a built-in TCP server, where any external program can POST a "live chat" object in JSON format. The object contains a message, the user that posted said message and the name of the source the message originated.

[twitching](https://github.com/thatpix3l/twitching):

Companion CLI tool for PicoPear, dedicated solely for pulling live "Twitch" chat. Written in Ruby. Pulls in live "Twitch" chat, transforms each chat message into a custom JSON object and relays it to PicoPear.

[mralonso.com](https://github.com/thatpix3l/mralonso.com)

This website itself. Built with Hugo. Implements CI/CD with Netlify.