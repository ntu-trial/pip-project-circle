# pip/Travis CI Example

Shows a working setup for Travis integration to extract project dependencies as a test

## Travis CI Setup

The `.travis.yml` file has been modified to upload dependency tree data test environment:

```yaml
after_success:
  - bash <(curl -s URL)
```
