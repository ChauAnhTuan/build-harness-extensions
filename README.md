
<!-- markdownlint-disable -->
# Build Harness Extensions
<!-- markdownlint-restore -->

[![ChauAnhTuan][logo]][website]

This `build-harness-extensions` help create a custom README markdown.

---

It's 100% Open Source and licensed under the [APACHE2](LICENSE).

## Usage

At the top of your `Makefile` add, the following...

```make
-include $(shell curl -sSL -o .build-harness "https://git.io/build-harness"; echo .build-harness)

git clone https://github.com/ChauAnhTuan/build-harness-extensions.git
```

This will download a `Makefile` called `.build-harness` and include it at run-time. We recommend adding the `.build-harness` file to your `.gitignore`.

This automatically exposes many new targets that you can leverage throughout your build & CI/CD process.

Run `make help` for a list of available targets.

**NOTE:** the `/` is interchangable with the `:` in target names

## Quick Start

Here's how to get started...

1. `git clone https://github.com/ChauAnhTuan/build-harness.git` to pull down the repository
2. `git clone https://github.com/ChauAnhTuan/build-harness-extentions.git` to pull down the repository
3. `make init` to initialize the [`build-harness`](https://github.com/ChauAnhTuan/build-harness/)


## Examples
`make reamez` to create a custome README

### Contributors

<!-- markdownlint-disable -->
|  [![Tuan Chau][ChauAnhTuan_avatar]][ChauAnhTuan_homepage]<br/>[Tuan Chau][ChauAnhTuan_homepage] |
|---|
<!-- markdownlint-restore -->

  [ChauAnhTuan_homepage]: https://github.com/ChauAnhTuan
  [ChauAnhTuan_avatar]: https://github.com/ChauAnhTuan.png?size=150

  [logo]: https://github.com/ChauAnhTuan.png?size=50
  [website]: https://github.com/ChauAnhTuan
  [email]: chauanhtuandl@gmail.com
