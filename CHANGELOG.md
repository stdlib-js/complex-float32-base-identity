# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-05-19)

<section class="features">

### Features

-   [`8ab1153`](https://github.com/stdlib-js/stdlib/commit/8ab1153533c1dcbe7eb1ce05590843dbeffa67e7) - update `complex/float32/base/identity` to accept stdlib complex numbers [(#6235)](https://github.com/stdlib-js/stdlib/pull/6235)
-   [`31343c9`](https://github.com/stdlib-js/stdlib/commit/31343c901e94328361327c4d7054a71052599916) - add `complex/float32/base/identity`

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`8ab1153`](https://github.com/stdlib-js/stdlib/commit/8ab1153533c1dcbe7eb1ce05590843dbeffa67e7): use stdlib C complex64 dtype

    -   To migrate, users should provide a value having the type `stdlib_complex64_t`, rather than a built-in C99 single-precision complex dtype. This dtype is available via the package `@stdlib/complex-float32/ctor`.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`8ab1153`](https://github.com/stdlib-js/stdlib/commit/8ab1153533c1dcbe7eb1ce05590843dbeffa67e7) - **feat:** update `complex/float32/base/identity` to accept stdlib complex numbers [(#6235)](https://github.com/stdlib-js/stdlib/pull/6235) _(by Gururaj Gurram)_
-   [`31343c9`](https://github.com/stdlib-js/stdlib/commit/31343c901e94328361327c4d7054a71052599916) - **feat:** add `complex/float32/base/identity` _(by Gururaj Gurram)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Gururaj Gurram
-   Karan Anand

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

