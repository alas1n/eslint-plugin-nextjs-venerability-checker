# eslint-plugin-nextjs-venerability-checker

This plugin is used to check for vulnerabilities in the nextjs project.

## Installation

```bash
pnpm install eslint-plugin-nextjs-venerability-checker
```

## Usage

You can Add this plugin to default nextjs eslint configuration.

```json
{
    "extends": "next",
    "plugins": [
        "nextjs-venerability-checker"
    ],
    "rules": {
        "nextjs-venerability-checker/<CVE-code>": "error"
    }
}
```


## Supported CVEs

- [CVE-2024-34351](https://github.com/advisories/GHSA-fr5h-rqp8-mj6g)
