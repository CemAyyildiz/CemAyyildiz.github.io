# Repo guide — which repo does what?

| Repo | Purpose | URL |
|------|---------|-----|
| **[CemAyyildiz.github.io](https://github.com/CemAyyildiz/CemAyyildiz.github.io)** | Portfolio site source (`index.html`) + **repo README** | [cemayyildiz.github.io](https://cemayyildiz.github.io/) |
| **CemAyyildiz** *(optional, not created yet)* | README on your **GitHub profile page** (`github.com/CemAyyildiz`) | — |
| **[CV](https://github.com/CemAyyildiz/CV)** | Old minimal CV (`index.html` only) | [cemayyildizcv.vercel.app](https://cemayyildizcv.vercel.app) |

## Important distinction

- **`README.md` in `CemAyyildiz.github.io`** → shows on the [repo page](https://github.com/CemAyyildiz/CemAyyildiz.github.io), not on your profile landing.
- **Profile README** (big intro on `github.com/CemAyyildiz`) → only works if you create a repo named exactly **`CemAyyildiz`** (same as username).

For most people: **bio + pinned repos + `CemAyyildiz.github.io` README** is enough. Profile repo is optional.

---

## Deploy README to CemAyyildiz.github.io

From this project root:

```bash
git add README.md
git commit -m "Add portfolio README"
git push
```

README appears at: https://github.com/CemAyyildiz/CemAyyildiz.github.io

---

## Optional: profile README on github.com/CemAyyildiz

1. Create public repo **`CemAyyildiz`** (name must match username)
2. Copy `profile/README.md` → `README.md` in that repo
3. Push

Same English content; remove the “This repo → portfolio site” line if you use it there.

---

## Bio text

See [BIO.md](BIO.md) for copy-paste bio and profile fields.
