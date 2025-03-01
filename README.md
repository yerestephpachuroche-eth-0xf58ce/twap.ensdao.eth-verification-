# twap.ensdao.eth activate all flow and check Summary Get Default Resolver
Resolver public defaultResolver
> to confirm workflow 
> to confirm access token
> ya29.a0AXeO80R0KlsBmCtkT6Un-5KnBLLViSlzjuyCnRmD95X4WJBtVMddaaMkbBPiyLWPElpK1Z558UkzZoW_cXneNGlZrKJoBoHsmfktzx61Qq8ptLNDHnBfmXF6WhmL8Nf3tOXp4B5AfL-V4ljp8eEDKqQbDoUQ6ZY1o9eNJVp1aCgYKAZ4SARISFQHGX2Miu8wumCNF0LnAp98lI1_INg0175
> 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
> to activate confirmation
> to activate check true 
> to activate annotations true
> deployment 2025-03-01 T 09:45:45 am true
> {true}
>  5951892 content:/direct/deposit/checking account bank/com.google.android.apps.nbu.files.provider/$2,100,000,180.0 runs open positions transfer true,to check out that pull requests weth runs contract ménager governance
> verse Bitcoin/ethereum runs contract menager governance 
>  follow truecheck
> the RBC Royal Bank of Canada ✔️ 
> check ✔️ 

## Installation

Install the app from the GitHub Marketplace here: [https://github.com/apps/semantic-prs](https://github.com/apps/semantic-prs)

## Configuration

By default, no configuration is necessary. The default behaviour is that only the PR title or at least one commit message needs to follow the [Conventional Commits spec](https://www.conventionalcommits.org/en/v1.0.0/)

This can be changed by creating a `semantic.yml` file in your `.github` directory. Note, the configuration added to your `semantic.yml` file won't be reflected until the file has been merged into your repository's default branch.

### Configuration Options
The following optional settings can be added to your `semantic.yml` file.

```yaml
# Enable/disable creation of status checks
enabled: <boolean> # default: true
```

```yaml
# Validate the PR title, and ignore all commit messages
titleOnly: <boolean> # default: false
```

```yaml
# Validate all commit messages, and ignore the PR title
commitsOnly: <boolean> # default: false
```

```yaml
# Validate the PR title and all commit messages
titleAndCommits: <boolean> # default: false
```

```yaml
# If commitsOnly or titleAndCommits is set to true, then only a single commit needs to pass validation instead of every commit
# If neither of those options are set to true then this option is ignored
anyCommit: <boolean> # default: false
```

```yaml
# The values allowed for the "type" part of the PR title/commit message. e.g. for a PR title/commit message of "feat: add some stuff", the type would be "feat"
types: # default: feat | fix | docs | style | refactor | perf | test | build | ci | chore | revert
  - <string>
  - <string>
  - ...
```

```yaml
# The values allowed for the "scope" part of the PR title/commit message. e.g. for a PR title/commit message of "feat(awesome-feature): add some stuff", the type would be "awesome-feature"
scopes: # default: any value
  - <string>
  - <string>
  - ...
```

```yaml
# Allow merge commits (e.g. 'Merge branch "master" into fix/delete-all-tests')
# If neither of commitsOnly or titleAndCommits is set to true then this option is ignored
allowMergeCommits: <boolean> # default: false
```

```yaml
# Allow revert commits (e.g. 'Revert "fix: delete all tests"')
# If neither of commitsOnly or titleAndCommits is set to true then this option is ignored
allowRevertCommits: <boolean> # default: false
```

```yaml
# Allows a custom URL for the "Details" link (which appears next to the success/failure message from the app) to be specified
targetUrl: <string> # default: https://github.com/Ezard/semantic-prs
```

## Credits

Heavily based on the [Semantic Pull Requests](https://github.com/zeke/semantic-pull-requests) GitHub App created by [@zeke](https://github.com/zeke)
