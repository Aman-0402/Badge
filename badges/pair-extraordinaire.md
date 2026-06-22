# Pair Extraordinaire

## What It Is
Awarded for co-authoring a commit that gets included in a merged pull request. Has four tiers.

## Tiers

| Tier | Co-authored PRs Merged |
|------|----------------------|
| Bronze | 1 |
| Silver | 10 |
| Gold | 24 |
| Platinum | 48 |

## How to Earn It

Add a `Co-authored-by:` trailer to a git commit message. That commit must be in a pull request that gets merged.

```
Co-authored-by: Full Name <email@example.com>
```

The email must match a GitHub account — otherwise GitHub cannot credit the co-author.

## Step by Step

**Step 1 — Create a branch and make a change**
```bash
git checkout -b pair-feature
echo "change" >> README.md
```

**Step 2 — Commit with the co-author trailer**
```bash
git commit -m "feat: add something useful

Co-authored-by: Friend Name <friend@github-email.com>"
```

**Step 3 — Push and open a PR**
```bash
git push origin pair-feature
```
Open PR on GitHub → merge it.

Both you and your co-author get the badge.

## Finding Your Co-author's Email

Ask your collaborator to check:
- GitHub → Settings → Emails → their primary or noreply email
- Noreply format: `username@users.noreply.github.com`

## Tips

- Both people earn the badge when the PR merges — even if one person didn't write code
- Works on your own repos — no need to contribute to someone else's project
- The co-author must have a GitHub account linked to the email used

## Status in This Repo

Aman: ✅ Earned via PR #7 with co-author Pallavi Kumari (June 2026)
