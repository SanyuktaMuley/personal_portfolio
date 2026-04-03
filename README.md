# Portfolio — Sanyukta Muley

Static personal portfolio (HTML + CSS).

**Live site (after you push & Pages is on):** [https://sanyuktamuley.github.io/personal_portfolio/](https://sanyuktamuley.github.io/personal_portfolio/)

**Repository:** [github.com/SanyuktaMuley/personal_portfolio](https://github.com/SanyuktaMuley/personal_portfolio)

## Push from your Mac

The remote `origin` should already point at your GitHub repo. In **Terminal** (so Git can sign you in):

```bash
cd /Users/sanyukta/Downloads/portfolio
git push -u origin main --force-with-lease
```

If Git says histories are unrelated or the push is rejected:

```bash
git push -u origin main --force
```

When asked for credentials, use your GitHub username and a **[Personal Access Token](https://github.com/settings/tokens)** (classic) with `repo` scope, or sign in via GitHub Desktop / SSH.

## GitHub Pages

Repo → **Settings** → **Pages** → Source: **Deploy from a branch** → Branch **main**, folder **/ (root)** → Save. Your shareable link is:

`https://sanyuktamuley.github.io/personal_portfolio/`

(If your GitHub username differs, replace `sanyuktamuley` with your profile name in the URL.)

## Run locally

```bash
cd /Users/sanyukta/Downloads/portfolio
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).
