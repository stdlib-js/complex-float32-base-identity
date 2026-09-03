# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2026-09-03)

<section class="commits">

### Commits

<details>

-   [`10ee0a5`](https://github.com/stdlib-js/stdlib/commit/10ee0a56ed60ae3d051ff0426b8e203a29c44cdc) - **chore:** clean-up [(#13754)](https://github.com/stdlib-js/stdlib/pull/13754) _(by Philipp Burckhardt)_
-   [`9f41dab`](https://github.com/stdlib-js/stdlib/commit/9f41daba5e816a9e63c3b0fbfb810cee8bb01258) - **bench:** refactor to use string interpolation in `complex` [(#11620)](https://github.com/stdlib-js/stdlib/pull/11620) _(by Karan Anand)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Karan Anand
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.1">

## 0.1.1 (2026-02-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2026-01-29)

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

-   [`7483bef`](https://github.com/stdlib-js/stdlib/commit/7483bef13b1d3241347266d25a02957269419825) - **test:** use .strictEqual() instead of .equal() _(by Philipp Burckhardt)_
-   [`d1c3e38`](https://github.com/stdlib-js/stdlib/commit/d1c3e38f0b788040e73f2ae4c6402e1d1337697c) - **docs:** update examples for `complex/float32/base/identity` [(#7289)](https://github.com/stdlib-js/stdlib/pull/7289) _(by Shabareesh Shetty)_
-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`8ab1153`](https://github.com/stdlib-js/stdlib/commit/8ab1153533c1dcbe7eb1ce05590843dbeffa67e7) - **feat:** update `complex/float32/base/identity` to accept stdlib complex numbers [(#6235)](https://github.com/stdlib-js/stdlib/pull/6235) _(by Gururaj Gurram)_
-   [`31343c9`](https://github.com/stdlib-js/stdlib/commit/31343c901e94328361327c4d7054a71052599916) - **feat:** add `complex/float32/base/identity` _(by Gururaj Gurram)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 4 people contributed to this release. Thank you to the following contributors:

-   Gururaj Gurram
-   Karan Anand
-   Philipp Burckhardt
-   Shabareesh Shetty

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

