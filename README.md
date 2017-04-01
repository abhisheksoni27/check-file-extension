# check-file-extension
Check the extension of any file being transported to your module via **extra-terrestial tunnels**, or, as the folks call it, **terminal**. (I am not sorry, Microsoft.)

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Examples](#examples)
* [Contributing](#contributing)
* [Legal stuff](#legal-stuff)

## Installation

Ask your terminal buddy to eat this burrito:

```bash
$ yarn add check-file-extension
```

In case your terminal is a vegan, you could also try this,

```bash
$ npm install check-file-extension
```

Terrible things are about to happen. Go Ahead!

## Usage

> **Step 1**
You need to bring the food you want to eat, right?

```js
const cfe = require('check-file-extension');
```

> **Step 2**
Then, you gotta just eat it.

```js
cfe('hermioneGranger.md'); // returns .md
```

That's it. Go nuts.

## Examples 

1. When you are being fed a file which is in the same house as you are:

```js
cfe('thisismyhouse.txt'); // returns .txt
```
2. When the file has established its tent somewhere else:
```js
cfe('myHouse/howYouDoin.png'); //returns .png (Also, I am doing fine baby, How you doin'?)
```

## Contributing

> **Step 1** 

Fork(**Fork**) this repository.

> **Step 2**

**Clone** the forked repository so that you now have a local build of this **brilliant tool.**

> **Step 3**

Add brilliance to it.

> **Step 4**

Send a **PR**. Pull Request, I mean. Ain't no **Embassy Office** here, all right.

## Legal Stuff

(Because shit might get real)

**MIT License**

Copyright (c) 2017-eternity Abhishek Soni

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.