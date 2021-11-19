<h1 align="center">Renovate config</h1>

Setup
-----

Set the `renovate.json` file like so:
```json
{
  "extends": [
    "github>benjaminmal/renovate-config"
  ]
}
```

Presets
-------

### Library
Use it with: `github>benjaminmal/renovate-config:library`
```json
{
  "extends": [
    "github>benjaminmal/renovate-config"
  ],
  "rangeStrategy": "widen"
}
```

### Project
Use it with: `github>benjaminmal/renovate-config:library`
```json
{
  "extends": [
    "github>benjaminmal/renovate-config"
  ],
  "rangeStrategy": "bump"
}
```
