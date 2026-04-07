# Contributing to Awesome No-Subscription

Thank you for helping build this list! Before submitting a pull request, please read these guidelines carefully.

## Criteria for Inclusion

Every entry must meet **all** of these requirements:

1. **Genuinely one-time purchase, free, or open source.** No subscription required for core functionality.
2. **Not freemium bait.** The free or paid version must be fully functional, not a crippled trial.
3. **Actively maintained.** Updated within the last two years, or stable enough to not need updates.
4. **Quality alternative.** Must genuinely replace the subscription software it claims to.
5. **Transparent pricing.** Pricing clearly stated on the official website.

## Verification Checklist

Before submitting, verify each of these:

- [ ] I visited the official website and confirmed the pricing model
- [ ] The software is genuinely one-time purchase, free, or open source
- [ ] There is no hidden subscription required for core features
- [ ] The software has been updated within the last 2 years (or is stable/mature)
- [ ] I tested or personally used this software (preferred but not required)
- [ ] The entry follows the exact format used in existing entries
- [ ] The link points to the official website, not a third-party mirror
- [ ] The "Replaces" field names a real subscription product with an accurate price

## Entry Format

Every entry must follow this exact format:

```markdown
### [Software Name](https://official-website.com)
<emoji> $XX one-time / Free / Open source (free) | Platforms
**Replaces:** Subscription Software ($XX/mo)
Brief description of what it does and why it is a good alternative.
```

**Emoji legend:**
- :moneybag: = One-time purchase
- :free: = Free (no payment required)
- :unlock: = Open source

## Pull Request Template

When submitting a PR, include:

1. **Software name and category** -- which file does it belong in?
2. **Verification** -- how did you verify the pricing model?
3. **Personal experience** -- have you used this software? For how long?
4. **Why it belongs** -- what subscription software does it replace, and why is it a good alternative?

## What We Do NOT Accept

- Software that was one-time purchase but has since moved to subscription-only
- "Free trials" or time-limited demos
- Software requiring a subscription for basic functionality (even if there is a free tier with crippled features)
- Abandonware with no updates in 3+ years and known security issues
- Duplicate entries (check existing lists first)
- Self-promotion without disclosure

## Updating Existing Entries

If a listed software changes its pricing model:

- **Moved to subscription:** Remove the entry and note the change in your PR description
- **Price changed:** Update the price and note it in your PR
- **New platforms:** Add the platforms to the existing entry

## Code Style (Python scripts)

Any Python scripts in this repository use a **line length of 120 characters** (configured in `pyproject.toml`).

## Code of Conduct

Be respectful, constructive, and focused on helping people find great software. This is a community resource, not a battleground for software preferences.

## Questions?

Open an issue if you are unsure whether a piece of software qualifies. We would rather discuss it first than reject a well-intentioned PR.
