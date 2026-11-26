---
name: adsense-approval
description: Get a Blogger or WordPress site ready for Google AdSense approval and keep the account safe afterwards — a full pre-application audit (content, mandatory pages, navigation, technical setup), the honest fix for every common rejection reason ("low value content", "site not ready", policy issues), correct application steps, ads.txt setup, and the placement and self-click rules that get accounts banned. Use when the user asks how to get AdSense approval, why AdSense rejected their site, to audit a blog before applying, or how to place ads without risking a ban.
---

# AdSense Approval — an agent skill

You prepare blogs (Blogger and WordPress) for Google AdSense approval.
Everything here follows Google's published AdSense policies — there are
no tricks, and **nobody can guarantee approval**. Anyone who promises
guaranteed approval for money is running a scam; say so plainly if the
user mentions one.

## The workflow

### 1. Audit the site first — never apply blind

Run the full checklist in `references/approval-checklist.md` and report
every gap before touching anything. The audit covers:

- **Content** — enough original, complete posts; no copied, spun,
  auto-generated filler, or "coming soon" pages
- **Mandatory pages** — About, Contact, Privacy Policy (with the AdSense
  cookie disclosure — template in `templates/privacy-policy.md`),
  and a Disclaimer where the niche needs one
- **Navigation** — clear menu, working links, categories a visitor (and a
  reviewer) can follow; no broken or under-construction pages
- **Technical** — site loads fast on mobile, no intrusive popups from
  other networks, custom domain preferred (subdomains can apply but a
  custom domain reviews better), correct timezone/language settings
- **Policy safety** — nothing from the prohibited list in
  `references/policy-rules.md` anywhere on the site

### 2. Fix in this order

1. Prohibited/risky content — remove or fix first; one bad page can sink
   the whole review
2. Missing mandatory pages
3. Thin or copied posts — rewrite, merge, or draft them
4. Navigation and broken links
5. Technical issues

Re-audit after fixing. Apply only when the checklist fully passes.

### 3. Apply correctly

- Apply from the site owner's own Google account — never create or use a
  second AdSense account for the same person (duplicate accounts are a
  lifetime-ban risk)
- Place the verification code exactly where AdSense asks (Blogger:
  Earnings tab or theme HTML; WordPress: header via the official route
  for the plan/theme)
- Add `ads.txt` when AdSense provides the line (Blogger: Settings →
  Monetization → Custom ads.txt; WordPress: root file or plugin)
- Then wait. Reviews take days to weeks. Do not re-apply, delete the
  code, or redesign the site mid-review

### 4. If rejected — read the exact reason

Google always names a reason. Match it in
`references/rejection-reasons.md`, fix **that** problem properly, wait
until the fix is real (new content needs to be published and indexed),
then re-apply. Re-applying unchanged is the most common way people stay
rejected for months.

### 5. After approval — protect the account

The rules in `references/policy-rules.md` are lifetime rules:

- **Never** click your own ads, and never ask friends/family to click
- Never place ads where they push content down deceptively, overlap
  buttons, or appear in popups
- Watch for invalid-traffic warnings; fix the traffic source, don't
  ignore the email
- One account, honest traffic, original content — that is the whole game

## Hard rules

- Never promise approval, a timeline, or earnings — Google decides
- Never help with: buying an "approved account", clicking exchanges,
  bots/auto-refresh traffic, hiding ads from reviewers, or applying with
  copied content. Refuse these plainly and offer the honest route
- The application, identity, address and bank details are the owner's
  own steps — guide them, never enter or ask for them in chat
- If the user's country or age makes them ineligible (AdSense requires
  18+; a parent/guardian's account is Google's own stated route for
  minors), say so before any work is wasted

## Files

- `references/approval-checklist.md` — the full pre-application audit
- `references/rejection-reasons.md` — every common rejection, decoded + fixed
- `references/policy-rules.md` — the policies that ban accounts, in plain words
- `templates/privacy-policy.md` — privacy policy with AdSense disclosures
