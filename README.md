# steveypagerio.com

T-SHIRTS project site. Built from scratch. Hosted on GitHub Pages.

Repo: https://github.com/stevey007/steveypagerio

## Turn on GitHub Pages

1. Open https://github.com/stevey007/steveypagerio/settings/pages
2. Source: **Deploy from a branch**
3. Branch: **main** / folder: **/ (root)**
4. Save

Temporary URL after that:
`https://stevey007.github.io/steveypagerio/`

## Point steveypagerio.com at it

A `CNAME` file is already in the repo (`steveypagerio.com`).

At your domain registrar, set DNS:

**If the registrar supports ALIAS / ANAME for the root domain**
- `steveypagerio.com` ALIAS/ANAME → `stevey007.github.io`
- `www` CNAME → `stevey007.github.io`

**If not, use GitHub Pages A records for the root**
- A `steveypagerio.com` → `185.199.108.153`
- A `steveypagerio.com` → `185.199.109.153`
- A `steveypagerio.com` → `185.199.110.153`
- A `steveypagerio.com` → `185.199.111.153`
- CNAME `www` → `stevey007.github.io`

Then in Pages settings, add custom domain `steveypagerio.com` and tick **Enforce HTTPS** once the certificate is ready (can take up to an hour).

## Edit the site

- `index.html` — page content
- `styles.css` — look
