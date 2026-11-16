# Shelf test extension

A test fixture for the end-to-end checks of [Shelf](https://github.com/niduslabs-dev/shelf), the Nidus Labs extension registry. It does nothing. Don't install it.

- `manifest.json` is the whole extension: Manifest V3, the `storage` permission, no code.
- `shelf.json` is Shelf's claim file, listing who may publish this extension's ID.
- Each GitHub Release carries the signed `.crx` for that version. The signing key is not in this repo.
