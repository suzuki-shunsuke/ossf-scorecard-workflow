# ossf-scorecard-workflow

[GitHub Actions reusable workflow](https://docs.github.com/en/actions/using-workflows/reusing-workflows) for [OpenSSF Scorecard](https://github.com/ossf/scorecard)

## Required permisions

- `security-events: write`
- `id-token: write`

## Example

```yaml
jobs:
  ossf-scorecard:
    uses: suzuki-shunsuke/ossf-scorecard-workflow/.github/workflows/ossf-scorecard.yaml@main
    permissions:
      security-events: write
      id-token: write
```

## LICENSE

[MIT](LICENSE)
