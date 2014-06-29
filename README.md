# viewfinder

## Installation

**From npm:**

```sh
npm install viewfinder
```

**Or github:**

```sh
git clone https://github.com/chbrown/viewfinder.git
cd viewfinder
npm install -g
```

**Import:**

```js
var viewfinder = require('viewfinder');
```


## References

- **epeg** is a libjpeg enhancement specially designed for downsampling. It reads only the part of the file that it needs in order to create a thumbnail of the size you specify. Very fast, very destructive.
  * [website](http://www.systhread.net/texts/200507epeg1.php), points upstream to [enlightenment.org](http://enlightenment.org/), but neither seem to have the source. See next item.
  * [source](https://github.com/mattes/epeg). Easy to build, simple `./configure && make && make install` gives you an easy-to-use `epeg` command on PATH.
  * [npm wrapper: epeg](https://www.npmjs.org/package/epeg). Not yet tested.

- **libjpeg-turbo**
  * `brew install libjpeg-turbo`
  * [website](http://www.libjpeg-turbo.org/)



## License

Copyright © 2014 Christopher Brown. [MIT Licensed](LICENSE).
