# Assert.js

this Assert.js is porting of [Node.js standard assertion library] for browser.
original code and test is comming from node.js, and modify them to browser compatible.

you can use this Assert.js for testing on browser.
for example [Mocha](http://visionmedia.github.com/mocha/) can test on bi-side, but dosen't has assertion itself.


## run test in **bi-side**

actuary, this Assert.js can running on node.js too.
you can use node.js standard assert module when running mocha on node.js.
and same test will run on browser if you read this library in browser.
this helps you, when you writes **Bi-Side JavaScript**


## how to use

```html
<script src="assert.js"></script>
<script src="path/to/testing-framework.js"></script>
<script src="path/to/your/test.js"></script>
```

## running test of this library

### browser
open test/index.html in your browser,
and see the console.

### node.js

```shell
> node test/test-assert.js
All OK
```

## license

MIT as same as Node.js