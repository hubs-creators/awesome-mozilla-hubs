# Awesome Mozilla Hubs
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a curated list of resources for Mozilla Hubs & Hubs-Cloud Developers and Creators.

----

## Table of contents

<!--ts-->
* [Awesome Mozilla Hubs](#awesome-mozilla-hubs)
   * [Table of contents](#table-of-contents)
   * [Creation](#creation)
      * [Avatar Creators](#avatar-creators)
      * [Spoke](#spoke)
      * [Tools](#tools)
   * [Development](#development)
      * [Accessibility](#accessibility)
      * [Code Snippets](#code-snippets)
      * [DevOps](#devops)
      * [Hubs Client](#hubs-client)
      * [Libraries](#libraries)
      * [Reticulum](#reticulum)
   * [Hubs-Cloud Hosting](#hubs-cloud-hosting)
      * [Self Hosting](#self-hosting)
   * [Other](#other)
      * [Bookmarklets](#bookmarklets)
   * [Community](#community)
   * [Contributing](#contributing)
   * [License](#license)
<!--te-->

----

## Creation

**[`^        back to top        ^`](#)**

- [Hubs Creator Labs](https://hubs.mozilla.com/labs/) - A blog for sharing inspiration, creativity and knowledge regarding Hubs creation.
- [Mozilla Hubs Youtube Channel](https://www.youtube.com/c/MozillaHubs/) - Lots of videos regarding content creation for Mozilla Hubs, including Material Setup, Light Baking, Virtual Cameras, Floor Plans, Waypoints, Hubs Blender Exporter, Avatars and more.


### Avatar Creators

- [Hubs Hackweek Avatar Maker](https://mozilla.github.io/hackweek-avatar-maker/) - Avatars that perform very well in Hubs with customizable eyes, hair-styles, skin-tones, freckles, clothing, accessories and more.
- [Ready Player Me](https://vr.readyplayer.me/de/avatar) - Avatars generated from a real photo of yourself with many customization options.
- [Rhiannan Berry Avatar Customizer](https://www.qt-mkr.com/) - Hubs compatible avatars, with a lot of customization options and the option to upload your own logo.

### Spoke

- [Introduction to Mirrors and Troika Text](https://www.youtube.com/watch?v=73RV0xbFD-c) - A short video tutorial on how to use Mirror and Troika Text components in Spoke.

### Tools

- [glbutils](https://github.com/msfeldstein/glb-utils) - Command line utility for inspecting and modifying gltf binary files.
- [glTF Sample Viewer](https://github.khronos.org/glTF-Sample-Viewer-Release/) - Tool to inspect gltf/glb files.
- [VARTISTE](https://vartiste.xyz/) - Open Source, web-based 3D art creation tool in your webbrowser for desktop and VR.


## Development

**[`^        back to top        ^`](#)**

- [Developer Talk: Understanding the Mozilla Hubs Code Base](https://vimeo.com/365531296) - Former engineering Lead Greg Fodor talks about the inner workings of Mozilla Hubs and the architectural decisions behind the project. ⚠️ Might be outdated.
- [Hubs Scripting Guide](https://github.com/aelatgt/hubs-scripting-guide) - Tutorial and template development environment for custom scripting.
- [Hubs System overview](https://github.com/mozilla/hubs/wiki/Hubs-system-overview) - Written overview of the Mozilla Hubs. ⚠️ Might be outdated.


### Accessibility

- [Using Mozilla Hubs with a Screen Reader](https://equalentry.com/mozilla-hubs-with-screen-reader/) - Experience report of using Mozilla Hubs with a screen reader (2020).


### Code Snippets

- [Simple note taking](https://gist.github.com/camelgod/debe1881f4f5000537261bcc5977291a) - Code snippet to integrate a the command `/note` for note taking.
- [Tools & Code snippets](https://fabien.benetou.fr/Tools/Hubs) - A collection of notes, experiments, tools and code snippets. Also see his [Github Gists](https://gist.github.com/Utopiah).
- [Trigger volume color box](https://gist.github.com/colinfizgig/34138f63b2f8a76e12b3691fb834fbe5) - A script to create a trigger volume test for Mozilla Hubs. It sets up a trigger-volume that changes the color of a box.


### DevOps

- [Automating Hubs Cloud Deployment Using CircleCI](https://xpportal.io/automating-hubs-cloud-deployment-using-circleci/) - Use CircleCI to maintain code quality and automatically deploy your custom Hubs Client.


### Hubs Client

- [Creating Networked Interactables](https://github.com/mozilla/hubs/blob/a98d7a62516aa19f11e38f32d2d6683d09643a9a/doc/creating-networked-interactables.md) - A tutorial on how to create new interactable objects. ⚠️ Might be outdated.
- [Custom Hubs Components](https://github.com/colinfizgig/Custom-Hubs-Components) - Guide and examples to create custom Hubs components.
- [Custom Video Geometry](https://xrhost.io/hubs-cloud-custom-video-geometry/) - Tutorial and example code on how to create a custom video geometry.
- [Research logger system](https://github.com/ayman/hubs/tree/hubs-cloud/src/systems/research) - Client side logger of user location and actions (not chat), which sends its data to a third party server for collection. Also see this [blog entry](https://ayman.medium.com/vr-research-in-mozilla-hubs-63fd3002eedf) for further details.
- [Extending Hubs with Code live in the browser](https://video.benetou.fr/w/qNBJU2GSjhBZwY7uUdd2iN) - Video of a community meetup, where Fabien Benetou explains how to change objects in Mozilla Hubs without installing anything.
- [Powering a Hubs Cloud homepage with WordPress – and beyond!](https://xpportal.io/powering-a-hubs-cloud-homepage-with-wordpress-and-beyond/) - Technical overview on how to get WordPress REST data to inject html content in your Hubs Cloud home page.


### Libraries

- [HubsCloudUtil](https://github.com/rawnsley/HubsCloudUtil) - A library, written in Kotlin, to access Mozilla Hubs rooms via the WebSocket Interface.


### Reticulum

- [Customizing Reticulum](https://github.com/kou029w/zenn.dev/blob/master/articles/hubs-custom-reticulum.md) - A guide (in Japanese) to customize reticulum.


## Hubs-Cloud Hosting

**[`^        back to top        ^`](#)**

- [Beyond monopolies: Mozilla Hubs on Digital Ocean](https://video.benetou.fr/w/7QPc8BQnwZBQZuxuwCuAhT) - Video tutorial on how to install Mozilla Hubs on Digital Ocean. Also see [this tutorial](https://video.benetou.fr/w/nxqC2ac8v93Tt7fXMQfygE), if you want to setup an internal database instead of a managed one.
- [Custom polycosm boot](https://gist.github.com/yakyouk/9ebe93232b2a094ae14f481279e8fcef) - Alternative instance boot script for Mozilla Hubs CF template 1.1.1, which among other things prevents automatic updates.


### Self Hosting

- [Docker Images](https://hub.docker.com/u/mozillareality) - Mozilla Hubs Docker images for their upcoming hosted service (project name: turkey). ⚠️ Not yet ready for production usage.
- [Hubs Installation Guide](https://github.com/albirrkarim/mozilla-hubs-installation-detailed) - Guide and documentation on how to run Mozilla Hubs locally or on a VPS.


## Other

**[`^        back to top        ^`](#)**


### Bookmarklets

- [hubs-bookmarklets](https://github.com/Exairnous/hubs-bookmarklets) -  A collection of bookmarklets (greyscale, toggle cursor, wireframe, solid shading, ...) to aid in the use of Mozilla Hubs.
- [Hubs Director](https://gist.github.com/gfodor/2ebdba84a49ba790bebe39aba2bee6ea) - Hubs Director Mode bookmarklet - Lets you easily create a custom lerp/slerp of the camera, optionally tracking a user, for recording nice videos in Hubs.
- [Print users to console](https://gist.github.com/gfodor/674ae6a1b43264d2efbd63d3cd65124e) - Prints all present user to browser console.
- [Streamer Mode](https://gist.github.com/gfodor/b63305340473ddc50698f92181140eab) - Toggle streamer mode via bookmarklet.


## Community

**[`^        back to top        ^`](#)**

- [Hubs Creators Meetup](https://www.meetup.com/hubs-creators-meetup/) -  Community meetup for Hubs Cloud Devs, 3D artists, designers, and webXR makers. They host workshops and tech talks around topics related to Mozilla Hubs, Blender and Spoke.
- [Taco Tuesday Testing Day](https://docs.google.com/spreadsheets/d/1T6y3sgMmycDErlSvEoYL2pQMuTJ7f0w8mtAZK7m2smg/edit#gid=0) - Weekly community led testing day to help each other test rooms and features. Also see the [event document for the TTTD by Imaginer and JTa](https://docs.google.com/document/d/1RmOEcLQM4B395rkGZ4eJJ5q9q6M4DcTBncxT8A6jbvs/edit).

----

## Contributing

Contribution guidelines can be found in [CONTRIBUTING.md](CONTRIBUTING.md).


## License

This list is licensed under the [Creative Commons Zero v1.0 Universal (CC0 1.0)](LICENSE) License.
