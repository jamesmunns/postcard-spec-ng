# Postcard Next-Generation Spec

This repo is tracking changes for the next version of the Postcard Specification.

It is written in [Typst](https://typst.app).

It is currently intended to be a minor revision, e.g. v1.1, and have no major changes to the Postcard Wire Format.

It is expected to add specifications for other pieces in the "Postcard ecosystem", including parts of `postcard-schema` and `postcard-rpc`.

This repo will be merged into [the main postcard repo](https://github.com/jamesmunns/postcard) when ready.

## Preview

You can build locally with `typst-cli`:

```sh
typst compile spec.typ --format pdf ./spec.pdf
```

You can preview the current version at [postcard.rs](https//postcard.rs).

## License

Like the main Postcard Specification, this repo is licensed under the terms of [CC-BY-SA 4.0](./LICENSE-CC-BY-SA).
