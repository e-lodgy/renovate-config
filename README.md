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

### Private repo
Use it with: `github>benjaminmal/renovate-config:private-repo`
```json
{
    "hostRules": [
        {
            "matchHost": "https://api.github.com/repos/benjaminmal/",
            "hostType": "github",
            "encrypted": {
                "token": "encryptedToken"
            }
        }
    ]
}
```
