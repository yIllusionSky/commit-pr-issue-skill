---
name: changelog
description: 用于记录项目开发和发布过程中的有意义变更，并维护 changelog、版本记录和发布说明。
---

# Changelog

## Rule

- 除固定关键词外，使用中文。
- 默认维护仓库根目录 `CHANGELOG.md`。
- 有意义的用户或工程变更，写入对应 `CHANGELOG.md` 的 `[Unreleased]` 区块；没有该区块时先创建。
- 发布 tag 时，将当前 `[Unreleased]` 标题改为 `[<version>] - <YYYY-MM-DD>`。
- `[Unreleased]` 只记录相对已发布版本的最终变化；同一未发布周期内的中间调整，应整理为最终状态，不单独记录过程。例如，未发布期间新功能被另一种实现替代时，只记录最终提供的功能，不记录替代过程。

## Template

```markdown
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

<!-- 新添加的功能。 -->

-

### Changed

<!-- 对现有功能的变更。 -->

-

### Deprecated

<!-- 已经不建议使用、未来会移除的功能。 -->

-

### Removed

<!-- 已经移除的功能。 -->

-

### Fixed

<!-- 对 bug 的修复。 -->

-

### Security

<!-- 对安全性的改进。 -->

-

## [<version>] - <YYYY-MM-DD>

...
```
