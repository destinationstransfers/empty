# empty
Empty package for testings / replacement purposes

Did you ever needed to omit a subdependency from installation?

You can do it with `yarn` and `resolutions` field in `package.json`:

```json
"resolutions": {
    "chromedriver": "git+https://github.com/destinationstransfers/empty.git"
}
```

:tada:
