# Blowfish Mod

Personal preferences for modifications to the [Hugo](https://github.com/gohugoio/hugo) theme [Blowfish](https://github.com/nunocoracao/blowfish).

## Usage

Edit `config/_default/module.toml`:

```toml
[[imports]]
disable = false
path = "github.com/nunocoracao/blowfish/v2"

[[imports]]
disable = false
path = "github.com/unacro/hugo-theme-blowfish-mod"
```

Then run `hugo server` to download automatically.

## Update

```bash
hugo mod get -u
```
