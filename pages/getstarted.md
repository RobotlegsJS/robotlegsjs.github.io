---
layout: page
title: Get started
permalink: /get_started/
---

RobotlegsJS is a architecture-based IoC framework for JavaScript/TypeScript. This
version is a direct port from the [ActionScript 3.0 codebase](https://github.com/robotlegs/robotlegs-framework).
See the [motivation](#motivation) behind it.

Right now, this framework have extensions for [pixi.js v4](http://www.pixijs.com) and
[phaser-ce v2.8](http://phaser.io).

Would you like to integrate RobotlegsJS core with another HTML5/JavaScript framework or library? Send us a message through [Gitter](https://gitter.im/RobotlegsJS/RobotlegsJS) or [Mail](mailto:contact@robotlegsjs.io).

**Features**

- Dependency injection (through [InversifyJS](https://github.com/inversify/InversifyJS))
- Command management
- View management

**Extensions**

- [RobotlegsJS-Macrobot](https://github.com/RobotlegsJS/RobotlegsJS-Macrobot): extends commands, adding support to async and macro commands.
- [RobotlegsJS-SignalCommandMap](https://github.com/RobotlegsJS/RobotlegsJS-SignalCommandMap): maps [SignalsJS](https://github.com/RobotlegsJS/SignalsJS) to commands.
- [RobotlegsJS-Pixi](https://github.com/RobotlegsJS/RobotlegsJS-Pixi): integrate RobotlegsJS with [PixiJS](http://www.pixijs.com).
- [RobotlegsJS-Pixi-Palidor](https://github.com/RobotlegsJS/RobotlegsJS-Pixi-Palidor): a view manager extension for [RobotlegsJS-Pixi](https://github.com/RobotlegsJS/RobotlegsJS-Pixi).
- [RobotlegsJS-Phaser](https://github.com/RobotlegsJS/RobotlegsJS-Phaser): integrate RobotlegsJS with [Phaser](http://phaser.io).
- [RobotlegsJS-Phaser-SignalCommandMap](https://github.com/RobotlegsJS/RobotlegsJS-Phaser-SignalCommandMap): maps [Phaser.Signal](https://photonstorm.github.io/phaser-ce/Phaser.Signal.html) to commands.

Motivation
===

There are plenty of frameworks and patterns out there that helps you to write
DOM-based applications. There is no scalable solution yet to architecture a
canvas-based application though.

[Robotlegs](http://www.robotlegs.org) has proven itself of being a mature solution from the ActionScript
community for interactive experiences.

License
===

[MIT](https://github.com/RobotlegsJS/RobotlegsJS/blob/master/LICENSE)