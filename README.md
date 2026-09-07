# SGS Fund website

Static copy of [www.sgs.fund](https://www.sgs.fund), hosted with GitHub Pages.

## Publishing

GitHub Pages publishes the `main` branch from the repository root. Pushing to
`main` updates the site automatically.

The custom domain is declared in `CNAME`. Its DNS records should be:

| Host | Type | Value |
| --- | --- | --- |
| `@` | `A` | `185.199.108.153` |
| `@` | `A` | `185.199.109.153` |
| `@` | `A` | `185.199.110.153` |
| `@` | `A` | `185.199.111.153` |
| `www` | `CNAME` | `jckdotim.github.io` |

Keep both the apex and `www` records so GitHub Pages can redirect the apex
domain to the canonical `www` hostname.
