Information for Code Climate CLI developers and contributors.

## Testing local changes

Build a new image using the local sources:

```console
docker build --rm -t codeclimate/codeclimate .
```

If you have the CLI installed, the `codeclimate` wrapper will automatically use
this image:

```console
codeclimate version
```

Otherwise, invoke the `docker run` command found in the README.

## Releasing a new version

```console
bin/release VERSION
```
