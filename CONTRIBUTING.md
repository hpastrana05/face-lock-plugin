# Contributing

Contributions are welcome through issues and pull requests.

Before opening a pull request:

```bash
./scripts/check
```

Keep the plugin compatible with Omarchy 4.x, do not edit Omarchy's packaged
files under `/usr/share/omarchy`, and preserve password authentication as a
fallback. Changes to PAM setup must be isolated, reversible, and documented.
