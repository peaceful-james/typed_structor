# Changelog

## [0.4.2](https://github.com/elixir-typed-structor/typed_structor/compare/v0.4.1...v0.4.2) (2024-07-11)


### Documentation

* this release is a documentation update and does not contain any new features or bug fixes


## [0.4.1](https://github.com/elixir-typed-structor/typed_structor/compare/v0.4.0...v0.4.1) (2024-07-10)


### Documentation

* this release is a documentation update and does not contain any new features or bug fixes


## [0.4.0](https://github.com/elixir-typed-structor/typed_structor/compare/v0.3.0...v0.4.0) (2024-07-07)


### ⚠ BREAKING CHANGES

* store parameters as keywords instead of atoms to retain more information ([#10](https://github.com/elixir-typed-structor/typed_structor/issues/10))

### Code Refactoring

* store parameters as keywords instead of atoms to retain more information ([#10](https://github.com/elixir-typed-structor/typed_structor/issues/10)) ([df5b17e](https://github.com/elixir-typed-structor/typed_structor/commit/df5b17e09cb569cb1c93c470db0e9eb322e429b8))

### Features

* add doc_fields guide ([#11](https://github.com/elixir-typed-structor/typed_structor/pull/11))

## [0.3.0](https://github.com/elixir-typed-structor/typed_structor/compare/v0.2.0...v0.3.0) (2024-07-03)


### ⚠ BREAKING CHANGES

* remove accessible plugin, add it to guides

### Bug Fixes

* macro capture will capture import context ([9c6f340](https://github.com/elixir-typed-structor/typed_structor/commit/9c6f3406009565b1e7ccab77d7ce24a7ee3984e6))


### Code Refactoring

* remove accessible plugin, add it to guides ([204cb0a](https://github.com/elixir-typed-structor/typed_structor/commit/204cb0aeab5a7ca8d5a15d7e016243d66af6e595))

## [0.2.0](https://github.com/elixir-typed-structor/typed_structor/compare/v0.1.5...v0.2.0) (2024-06-30)


### Features

* register plugins globally by configuration ([4767e62](https://github.com/elixir-typed-structor/typed_structor/commit/4767e620c237777f535cfe763c773d13a4944c0f))

## 0.1.5 (2024-06-29)

This release is a documentation update and
does not contain any new features or bug fixes.

## 0.1.4 (2024-06-29)

This release is a documentation update and
does not contain any new features or bug fixes.

## 0.1.3 (2024-06-29)

### Features
- doc: add `Migrate from typed_struct` guide

### Bug Fixes
- fix: exclude key from `@enforce_keys`, if `:default` is set and `:enforce` is true

## 0.1.2 (2024-06-29)

### Bug Fixes
- avoid enforcing the field when default is unset and enforce is false

## 0.1.1 (2024-06-28)

### Bug Fixes
- if default is set, then this field is enforced (#2)

## 0.1.0 (2024-06-28)

### Features
First release
