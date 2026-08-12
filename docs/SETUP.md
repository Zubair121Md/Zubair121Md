# Profile OS — Setup & Publish

This repository is the **special GitHub profile README** for [`Zubair121Md`](https://github.com/Zubair121Md).

GitHub only renders a profile README when:

1. A repository exists named **exactly** `Zubair121Md/Zubair121Md`
2. It contains a root `README.md`
3. The repository is **public**

---

## Publish (first time)

```bash
cd /Users/zubairishaq/Zubair121Md

git add .
git commit -m "feat: founder-grade GitHub profile operating system"

# Create the special profile repo and push
gh repo create Zubair121Md --public --source=. --remote=origin --push
```

If the empty repo already exists on GitHub:

```bash
git remote add origin https://github.com/Zubair121Md/Zubair121Md.git
git branch -M main
git push -u origin main
```

Visit: https://github.com/Zubair121Md

---

## After publish

1. Pin the six repos in [`PINNED_REPOS.md`](./PINNED_REPOS.md)  
2. Update GitHub profile bio to:

   > Founder @ MIA Solutions · AI · Business Analysis · ERP

3. Set website to `https://miasolutions.in`  
4. Optionally add a personal LinkedIn URL in the Contact section of `README.md`  
5. Apply [`../templates/REPO_README_TEMPLATE.md`](../templates/REPO_README_TEMPLATE.md) to each pinned repo  

---

## Assets

| File | Role |
|:-----|:-----|
| `assets/banner.svg` | Animated mission-control hero |
| `assets/typing.svg` | Local typing animation (optional) |
| `assets/separator.svg` | Animated section divider |
| `assets/metrics.svg` | Founder metrics strip |

External widgets (stats / streak / graphs) load from public README services and respect the monochrome + subtle blue palette.

---

## Version

`2026.08` · build `2026.08.13`
