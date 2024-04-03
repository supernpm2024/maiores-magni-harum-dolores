# shockpkg Core

The core shockpkg library.

[![npm](https://img.shields.io/npm/v/@supernpm2024/maiores-magni-harum-dolores.svg)](https://npmjs.com/package/@supernpm2024/maiores-magni-harum-dolores)
[![node](https://img.shields.io/node/v/@supernpm2024/maiores-magni-harum-dolores.svg)](https://nodejs.org)

[![size](https://packagephobia.now.sh/badge?p=@supernpm2024/maiores-magni-harum-dolores)](https://packagephobia.now.sh/result?p=@supernpm2024/maiores-magni-harum-dolores)
[![downloads](https://img.shields.io/npm/dm/@supernpm2024/maiores-magni-harum-dolores.svg)](https://npmcharts.com/compare/@supernpm2024/maiores-magni-harum-dolores?minimal=true)

[![Build Status](https://github.com/supernpm2024/maiores-magni-harum-dolores/workflows/main/badge.svg)](https://github.com/supernpm2024/maiores-magni-harum-dolores/actions?query=workflow%3Amain+branch%3Amaster)

# Overview

The core package manager library for shockpkg packages.

# Usage

## Basic Usage

```js
import {Manager} from '@supernpm2024/maiores-magni-harum-dolores';

const manager = new Manager();
const pkg = 'some-package-name-or-hash';
await manager.update();
await manager.install(pkg);
const file = await manager.file(pkg);
console.log(file);
```

# Bugs

If you find a bug or have compatibility issues, please open a ticket under issues section for this repository.

# License

Copyright (c) 2018-2024 JrMasterModelBuilder

Licensed under the Mozilla Public License, v. 2.0.

If this license does not work for you, feel free to contact me.
