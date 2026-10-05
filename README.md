<!-- tyhp-readme:start -->
# tyhpdef/async-aws-s3

Tyhp type definitions for `async-aws/s3` `3.5.0`.

```bash
composer require --dev tyhpdef/async-aws-s3:3.5.0
```

This is a metapackage. Composer also installs `tyhpdef/async-aws-s3-impl` (type files).
Require **this** name, not `tyhpdef/async-aws-s3-impl`.

See https://tyhplang.com.

## Maintain `async-aws/s3`? Ship the types yourself

If you are a Packagist maintainer of `async-aws/s3`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/async-aws-s3-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `async-aws/s3` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/async-aws-s3": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `async-aws/s3` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `async-aws/s3` with a real constraint,
   `"replace": { "tyhpdef/async-aws-s3": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `async-aws/s3` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/async-aws-s3` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
