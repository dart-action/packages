# CONTRIBUTING

Please submit changes to the main branch, and make sure your code is willing to comply with MIT style.

## About development

The repo is manage by [melos][], so you need to install it first.

```bash
dart pub global activate melos
```

Then you can run `melos bootstrap` to init the repo.

```bash
melos bootstrap
```

And run:

```bash
melos run get
```

to get all dependencies.

[melos]: https://melos.invertase.dev

### About CHANGELOG

The CHANGELOG for each package is independent.
When you submit a pull request, please also modify the CHANGELOG file with the changes.

If you don't have the current version of the section, you can add a secondary title

```md
## Unreleased

Feature:
- xxxx

Or 

Fix:
- xxx
```
