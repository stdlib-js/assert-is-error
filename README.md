<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# isError

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> Test if a value is an [Error][mdn-error] object.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->

<section class="installation">

## Installation

```bash
npm install @stdlib/assert-is-error
```

</section>

<section class="usage">

## Usage

```javascript
var isError = require( '@stdlib/assert-is-error' );
```

#### isError( value )

Tests if a `value` is an [`Error`][mdn-error] object.

```javascript
var bool = isError( new Error( 'beep' ) );
// returns true
```

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var isError = require( '@stdlib/assert-is-error' );

var bool = isError( new Error( 'error' ) );
// returns true

bool = isError( new EvalError( 'eval error' ) );
// returns true

bool = isError( new RangeError( 'range error' ) );
// returns true

bool = isError( new ReferenceError( 'reference error' ) );
// returns true

bool = isError( new SyntaxError( 'syntax error' ) );
// returns true

bool = isError( new TypeError( 'type error' ) );
// returns true

bool = isError( new URIError( 'URI error' ) );
// returns true

bool = isError( {} );
// returns false

bool = isError( null );
// returns false
```

</section>

<!-- /.examples -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-is-error.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-is-error

[test-image]: https://github.com/stdlib-js/assert-is-error/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/assert-is-error/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-is-error/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-is-error?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-is-error.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-is-error/main

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-is-error/main/LICENSE

[mdn-error]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error

</section>

<!-- /.links -->
