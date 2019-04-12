## Date2 ![NPM version](https://img.shields.io/npm/v/date2.js.svg?style=flat)

### Installation

```bash
$ npm install date2.js --save
```

### Example
```js
const Date2 = require('date2.js');

var date = new Date2();

date.toString('yyyy-MM-dd HH:mm:ss');

or

import Date2 from 'date2.js'

let date = new Date2(new Date());
date.toString('yyyy-MM-dd HH:mm:ss'); // 2019-04-12 19:42:11
date.now() // new 时候传入日期的 时间戳 。默认0
date.ago() // 49 years ago
date.parse('2015-10-01 12:10:00') // Thu Oct 01 2015 12:10:00 GMT+0800 (中国标准时间)
date.create({
  date: "01",
  fullYear: "2015-10-01",
  hour: "12",
  minute: "10",
  month: "10",
  second: "00",
  time: "12:10:00",
  year: "2015"
}) //Thu Oct 01 2015 12:10:00 GMT+0800 (中国标准时间)

```

### API
check this file: `index.js`

### Contributing
- Fork this Repo first
- Clone your Repo
- Install dependencies by `$ npm install`
- Checkout a feature branch
- Feel free to add your features
- Make sure your features are fully tested
- Publish your local branch, Open a pull request
- Enjoy hacking <3

### MIT license
Copyright (c) 2016 lsong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the &quot;Software&quot;), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED &quot;AS IS&quot;, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

---
