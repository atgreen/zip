# EGCL support

The `egcl` branch uses `EGCL-POSIX` for native pathname metadata.
Run from the repository root:

```sh
egcl --no-init --load tests/egcl-metadata.lisp
```

ZIP entry permissions use the native stat mode. Directory traversal depends
on the capabilities of the installed CL-FAD backend.
