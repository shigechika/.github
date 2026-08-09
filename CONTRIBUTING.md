# Contributing

Thanks for your interest in contributing! These are the default contribution
guidelines for [@shigechika](https://github.com/shigechika)'s repositories.
Individual repositories may add their own `CONTRIBUTING.md` with project-specific
details.

## Before you start

- **Search first.** Check existing issues and pull requests before opening a new
  one, to avoid duplicates.
- **Reproduce on the latest version.** For bug reports, please confirm the issue
  still occurs on the most recent release.
- **Open an issue for large changes.** For anything beyond a small fix, please
  open an issue to discuss the approach before investing time in a PR.

## Pull request workflow

- **Branch, don't push to `main`.** Never push directly to `main`; always work on
  a branch and open a pull request.
- **Branch names use Conventional Commits prefixes** — e.g. `feat/…`, `fix/…`,
  `docs/…`, `chore/…`.
- **Commit messages follow [Conventional Commits](https://www.conventionalcommits.org/)** —
  `feat:`, `fix:`, `docs:`, `chore:`, etc.
- **Keep PRs focused.** One logical change per PR is easier to review.
- **Update docs with code.** If your change affects behavior, update the relevant
  README / documentation in the same PR.
- **Make sure CI passes** before requesting review.

## Code review & merge

Pull requests are reviewed before merging. Merges are done as **squash merge**
with the branch deleted afterwards.

By contributing, you agree that your contributions will be licensed under the
same license as the repository.

---

# コントリビューションガイド（日本語）

貢献に興味を持っていただきありがとうございます。これは
[@shigechika](https://github.com/shigechika) の各リポジトリ共通の既定ガイドです。
各リポジトリはプロジェクト固有の内容を持つ `CONTRIBUTING.md` を追加で置くことがあります。

## 始める前に

- **まず検索を。** 重複を避けるため、既存の Issue / Pull Request を確認してください。
- **最新バージョンで再現確認を。** バグ報告の場合、最新リリースでも問題が発生するか
  確認してください。
- **大きな変更は先に Issue を。** 小さな修正を超える変更は、PR に着手する前に
  Issue で方針を相談してください。

## Pull Request の流れ

- **`main` に直接 push しない。** 必ずブランチを切って Pull Request を作成してください。
- **ブランチ名は Conventional Commits のプレフィックス**を使います（例: `feat/…`、
  `fix/…`、`docs/…`、`chore/…`）。
- **コミットメッセージは [Conventional Commits](https://www.conventionalcommits.org/) 形式**
  （`feat:`、`fix:`、`docs:`、`chore:` など）。
- **PR は目的を絞る。** 1 PR につき論理的に 1 つの変更だとレビューしやすいです。
- **コードと一緒にドキュメントも更新。** 挙動に影響する変更は、同じ PR で該当する
  README / ドキュメントを更新してください。
- レビュー依頼の前に **CI が通ること**を確認してください。

## レビューとマージ

Pull Request はマージ前にレビューされます。マージは **squash merge** で行い、
その後ブランチは削除します。

貢献いただいた内容は、当該リポジトリと同じライセンスの下で提供されることに
同意したものとみなします。
