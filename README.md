# node-inator

This is a simple Action to stage some Node stuff typically used in quality gates, releases, etc.

## Usage

To use it just make an action like this:

```yaml
jobs:
  setup-env:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: StoopidCompany/node-inator/.github/actions/node-inator@main
        with:
          node-version: "20"
```
