---
layout: page
title: Get started
permalink: /get_started/
---

RobotlegsJS is a architecture-based IoC framework for JavaScript/TypeScript. This
version is a direct port from the [ActionScript 3.0 codebase](https://github.com/robotlegs/robotlegs-framework).
See the [motivation](#motivation) behind it.

Right now, this framework has extensions for [pixi.js v4](https://github.com/pixijs/pixi.js), [easeljs](https://github.com/CreateJS/EaselJS),
[openfl](https://github.com/openfl/openfl), [phaser-ce v2](https://github.com/photonstorm/phaser-ce) and [phaser v3](https://github.com/photonstorm/phaser).

Would you like to integrate RobotlegsJS core with another HTML5/JavaScript framework or library? Send us a message through [Gitter](https://gitter.im/RobotlegsJS/RobotlegsJS) or [Email](mailto:contact@robotlegsjs.io).

# Features

- Dependency injection (through [InversifyJS](https://github.com/inversify/InversifyJS))

- Command management

- View management

# Extensions

- [RobotlegsJS-Macrobot](https://github.com/RobotlegsJS/RobotlegsJS-Macrobot): extends commands, adding support to async and macro commands.

- [RobotlegsJS-SignalCommandMap](https://github.com/RobotlegsJS/RobotlegsJS-SignalCommandMap): maps [SignalsJS](https://github.com/RobotlegsJS/SignalsJS) to commands.

- [RobotlegsJS-EventEmitter3](https://github.com/RobotlegsJS/RobotlegsJS-EventEmitter3): integrate RobotlegsJS with [EventEmitter3](https://github.com/primus/eventemitter3).

- [RobotlegsJS-Pixi](https://github.com/RobotlegsJS/RobotlegsJS-Pixi): integrate RobotlegsJS with [PixiJS](https://github.com/pixijs/pixi.js).

- [RobotlegsJS-Pixi-Palidor](https://github.com/RobotlegsJS/RobotlegsJS-Pixi-Palidor): a view manager extension for [RobotlegsJS-Pixi](https://github.com/RobotlegsJS/RobotlegsJS-Pixi).

- [RobotlegsJS-Pixi-SignalMediator](https://github.com/RobotlegsJS/RobotlegsJS-Pixi-SignalMediator): a port of [Robotlegs SignalMediator Extension](https://github.com/MrDodson/robotlegs-extensions-SignalMediator) to TypeScript.

- [RobotlegsJS-CreateJS](https://github.com/RobotlegsJS/RobotlegsJS-CreateJS): integrate RobotlegsJS with [EaselJS](https://github.com/CreateJS/EaselJS).

- [RobotlegsJS-OpenFL](https://github.com/RobotlegsJS/RobotlegsJS-OpenFL): integrate RobotlegsJS with [OpenFL](https://github.com/openfl/openfl).

- [RobotlegsJS-Phaser-CE](https://github.com/RobotlegsJS/RobotlegsJS-Phaser-CE): integrate RobotlegsJS with [Phaser-CE](https://github.com/photonstorm/phaser-ce).

- [RobotlegsJS-Phaser-CE-SignalCommandMap](https://github.com/RobotlegsJS/RobotlegsJS-Phaser-CE-SignalCommandMap): maps [Phaser.Signal](https://photonstorm.github.io/phaser-ce/Phaser.Signal.html) to commands.

- [RobotlegsJS-Phaser](https://github.com/RobotlegsJS/RobotlegsJS-Phaser): integrate RobotlegsJS with [Phaser](https://github.com/photonstorm/phaser).

# Motivation

There are plenty of frameworks and patterns out there that helps you to write
DOM-based applications. There is no scalable solution yet to architecture a
canvas-based application though.

[Robotlegs](https://github.com/robotlegs/robotlegs-framework) has proven itself of being a mature solution from the ActionScript
community for interactive experiences.

# License

[MIT](https://github.com/RobotlegsJS/RobotlegsJS/blob/master/LICENSE)
