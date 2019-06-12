blue-prod-util
===========

Shared utilities between blue-prod, waterline, etc.

## Help

If you have further questions or are having trouble, click [here](https://github.com/EMSA-TECHNOLOGY/blue-prod-util/issues).


## Bugs &nbsp; [![NPM version](https://badge.fury.io/js/blue-prod-util.svg)](http://npmjs.com/package/blue-prod-util)

To report a bug, [click here](https://github.com/EMSA-TECHNOLOGY/blue-prod-util/issues).


## Contributing

[![NPM](https://nodei.co/npm/blue-prod-util.png?downloads=true)](http://npmjs.com/package/blue-prod-util)

## Coming changes:
+ async
+ lodash
+ optimist
+ fs-extra
+ node-switchback
+ json-stringify-safe
+ underscore.str
+ core node `util`

> Most of these extra dependencies will be stripped in an upcoming version,
> in favor of requiring those dependencies directly in your app instead.
> This will make this module more lighweight and make all the things install and load faster.
>
> ##### Notable exceptions:
>
> + Certain commonly-used parts of `underscore.str`, e.g. `_.str.capitalize`
>   + (but these will be cherry-picked and bundled rather than including the entire dep)
> + json-stringify-safe will likely stay a dependency.
>
> ##### Things to add:
> + I'd like to bundle a few of the most commonly used methods from momentjs.

## License

The [blue-prod framework](https://github.com/EMSA-TECHNOLOGY/blue-prod) is free and open-source under the [MIT License](https://github.com/EMSA-TECHNOLOGY/blue-prod-hook-sockets/blob/master/LICENSE.md).