<!-- tyhp-readme:start -->
# tyhpdef/symfony-polyfill-intl-idn

Tyhp type definitions for `symfony/polyfill-intl-idn` `1.42.0`.

```bash
composer require --dev tyhpdef/symfony-polyfill-intl-idn:1.42.0
```

This is a metapackage. Composer also installs `tyhpdef/symfony-polyfill-intl-idn-impl` (type files).
Require **this** name, not `tyhpdef/symfony-polyfill-intl-idn-impl`.

See https://tyhplang.com.

## Maintain `symfony/polyfill-intl-idn`? Ship the types yourself

If you are a Packagist maintainer of `symfony/polyfill-intl-idn`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-polyfill-intl-idn-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/polyfill-intl-idn` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-polyfill-intl-idn": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/polyfill-intl-idn` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/polyfill-intl-idn` with a real constraint,
   `"replace": { "tyhpdef/symfony-polyfill-intl-idn": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/polyfill-intl-idn` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-polyfill-intl-idn` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
