# Create sentry release

Create a sentry release for a given project.

## Example Usage

```
  create-sentry-release:
    runs-on: ubuntu-latest
    steps:
      - uses: infrabits/ci-create-sentry-release@main
        with:
          api_key: very-secret-key
          organization: example-org
          project: example-project
          version: v1.0.0
          upload_sourcemaps: true
```
