# moneymate-privacy

Public hosting-only repo for the [MoneyMate iOS app](https://github.com/NguyenNgocThach131193/money-mate-ios) Privacy Policy.

**Live site**: https://nguyenngocthach131193.github.io/moneymate-privacy/

## How it works

The HTML on the `gh-pages` branch is auto-generated from `docs/privacy-policy.md` and `docs/privacy-policy-en.md` in the iOS repo by [`deploy-privacy-pages.yml`](https://github.com/NguyenNgocThach131193/money-mate-ios/blob/develop/.github/workflows/deploy-privacy-pages.yml).

Do **not** edit files on the `gh-pages` branch directly — they will be overwritten on the next sync. Edit the markdown source in the iOS repo instead.

## Why a separate repo

The iOS source repo is private; personal Free GitHub accounts cannot serve Pages from private repos. This public repo holds only the rendered policy HTML, which is public information anyway.
