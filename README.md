This a minimal repository to show a bug in Nuxt Content fetchNavigation

content dir has both a `_dir.yml` and `index.md` file. Metadata from `_dir.yml` is used, and metadata from `index.md` can't be found in the navigation.

If the `index.md` file is removed, metadata from `_dir.yml` can't be found in the navigation.

Subdirectories work as expected, see the `example` directory.
