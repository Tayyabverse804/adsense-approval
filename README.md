# AdSense Approval — an open-source agent skill

A skill that teaches an AI agent to **get a Blogger or WordPress site
ready for Google AdSense approval — honestly** — and to keep the
account safe after approval.

No tricks, no "guaranteed approval" nonsense (that is always a scam).
Just Google's own published policies turned into a working checklist:
audit → fix → apply → decode rejections → protect the account.

## What's inside

```
SKILL.md                            the workflow + hard rules
references/
  approval-checklist.md             the full pre-application audit
  rejection-reasons.md              "low value content" etc., decoded + fixed
  policy-rules.md                   the rules that ban accounts, in plain words
templates/
  privacy-policy.md                 privacy page with AdSense cookie disclosures
```

## What the agent does with it

1. **Audits** your site against the full checklist — content, mandatory
   pages, navigation, technical setup, policy safety — and names every
   gap before changing anything
2. **Fixes** in the right order: risky content first, then pages, then
   thin content, then navigation and technical issues
3. **Guides the application** — verification code, ads.txt, and what
   not to touch while Google reviews
4. **Decodes rejections** — matches Google's exact reason to the real
   fix, instead of re-applying unchanged
5. **Protects the account** — placement rules, invalid-click rules, and
   the one-account-for-life rule

## Install

Copy this folder into your agent's skills directory, for example:

- **Claude Code:** `~/.claude/skills/adsense-approval/`
- **Muse / other agents:** wherever your agent loads `SKILL.md` skills from

Then ask your agent things like:

- "Audit my blog — is it ready for AdSense?"
- "AdSense rejected me for low value content. What do I fix?"
- "Write my privacy policy with the AdSense disclosures"

## Honest note

Approval is Google's decision. This skill makes your site genuinely
ready and keeps you out of the traps — copied content, fake "approval
services", click exchanges — that end blogs and ban accounts for life.

## License

MIT — see `LICENSE`. Use it, fork it, improve it.

## Contributing

Issues and pull requests welcome: new rejection reasons as Google adds
them, platform-specific setup notes, and translations.
