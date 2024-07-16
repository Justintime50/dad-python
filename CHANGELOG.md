# CHANGELOG

## v2.0.0 (2024-07-16)

- Replaces `pkg_resources` with `importlib.resources` to properly load the included `dad` submodule
- Bumps `dad` submodule

## v1.1.1 (2023-12-04)

- Fixes releasing process to include the `dad` submodule

## v1.1.0 (2023-10-25)

**Build is broken, please use `v1.1.1` instead**

- Adds support for Python 3.12
- Bumps `dad` submodule

## v1.0.0 (2023-07-01)

- Drops support for Python 3.7

## v0.3.0 (2022-02-05)

- Adds French addresses
- Bumps dev dependencies

## v0.2.1 & v0.2.2 (2021-11-30)

- Adds `mypy` to run type checking and publishes types with new `py.typed` file

## v0.2.0 (2021-09-23)

- Properly reference DAD files in a package context using `pkg_resources`

## v0.1.0 - v0.1.7 (2021-09-10/13/22)

- Initial release allowing you to retrieve addresses from all around the world
- Various re-releases were required to properly package the DAD assets
