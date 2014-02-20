*This repository is a mirror of the [component](http://component.io) module [kewah/mixin](http://github.com/kewah/mixin). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/kewah-mixin`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
[![browser support](https://ci.testling.com/kewah/mixin.png)](https://ci.testling.com/kewah/mixin)

# mixin

  ES5 compatible mixin

## Installation

    $ component install kewah/mixin

## API

    var a = {
     foo: 'bar',
     toto: 'tata'
    };

    var b = {};

    mixin(b, a);

    assert(b.foo === 'bar');
    assert(b.toto === 'tata');

## License

  MIT
