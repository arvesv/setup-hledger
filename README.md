# setup-hledger
A GitHub action for installing hledger on the build agent.

## Usage

```yaml
steps:
  - uses: actions/checkout@v4
  - uses: arvesv/setup-hledger@v1
  - run: hledger --version
```
