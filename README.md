# eprolisagroup.com

Static site for **EPROLISA GROUP LLC**, hosted on GitHub Pages.

## Local preview

Open `index.html` in a browser, or serve the directory:

```bash
python3 -m http.server 8080
```

## GitHub Pages + custom domain

After this is merged to `main`:

1. In the repo **Settings → Pages**:
   - Source: **GitHub Actions**
2. At your DNS provider for `eprolisagroup.com`, add:

   | Type  | Name | Value                         |
   | ----- | ---- | ----------------------------- |
   | A     | `@`  | `185.199.108.153`             |
   | A     | `@`  | `185.199.109.153`             |
   | A     | `@`  | `185.199.110.153`             |
   | A     | `@`  | `185.199.111.153`             |
   | CNAME | `www`| `eduardchernomaz.github.io`   |

3. In **Settings → Pages**, set Custom domain to `eprolisagroup.com` and enable **Enforce HTTPS** once DNS propagates.

The repo includes a `CNAME` file for `eprolisagroup.com`.
