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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# getegid

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Return the effective numeric group identity of the calling process.



<section class="usage">

## Usage

```javascript
import getegid from 'https://cdn.jsdelivr.net/gh/stdlib-js/process-getegid@esm/index.mjs';
```

#### getegid()

Returns the effective numeric group identity of the calling process.

```javascript
var id = getegid();
```

</section>

<!-- /.usage -->

<section class="notes">

## Notes

-   The function **only** returns an `integer` group identity on POSIX platforms. For all other platforms (e.g., Windows, browsers, and Android), the function returns `null`. 
-   See [getegid(2)][getegid].

</section>

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import getegid from 'https://cdn.jsdelivr.net/gh/stdlib-js/process-getegid@esm/index.mjs';

var gid = getegid();
console.log( 'gid: %d', gid );

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/process-geteuid`][@stdlib/process/geteuid]</span><span class="delimiter">: </span><span class="description">return the effective numeric user identity of a calling process.</span>
-   <span class="package-name">[`@stdlib/process-getgid`][@stdlib/process/getgid]</span><span class="delimiter">: </span><span class="description">return the numeric group identity of a calling process.</span>
-   <span class="package-name">[`@stdlib/process-getuid`][@stdlib/process/getuid]</span><span class="delimiter">: </span><span class="description">return the numeric user identity of a calling process.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2025. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/process-getegid.svg
[npm-url]: https://npmjs.org/package/@stdlib/process-getegid

[test-image]: https://github.com/stdlib-js/process-getegid/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/process-getegid/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/process-getegid/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/process-getegid?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/process-getegid.svg
[dependencies-url]: https://david-dm.org/stdlib-js/process-getegid/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/process-getegid/tree/deno
[deno-readme]: https://github.com/stdlib-js/process-getegid/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/process-getegid/tree/umd
[umd-readme]: https://github.com/stdlib-js/process-getegid/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/process-getegid/tree/esm
[esm-readme]: https://github.com/stdlib-js/process-getegid/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/process-getegid/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/process-getegid/main/LICENSE

[getegid]: http://man7.org/linux/man-pages/man2/getegid.2.html

<!-- <related-links> -->

[@stdlib/process/geteuid]: https://github.com/stdlib-js/process-geteuid/tree/esm

[@stdlib/process/getgid]: https://github.com/stdlib-js/process-getgid/tree/esm

[@stdlib/process/getuid]: https://github.com/stdlib-js/process-getuid/tree/esm

<!-- </related-links> -->

</section>

<!-- /.links -->
