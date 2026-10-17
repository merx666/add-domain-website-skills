# Business Websites by Add Domain

An Agent Skill that turns a first "make me a website" request into a launch-ready small-business site: a working order, booking or enquiry path, copy from the owner's real facts, a phone-first layout, accessibility, search and share previews, local business data, launch checks and a handover the owner can maintain.

Works with Claude Code, Cursor, Codex, OpenClaw, Hermes and any agent that reads [Agent Skills](https://agentskills.io).

## Install

```sh
npx skills add vitaliiphangan-code/add-domain-website-skills --skill frontend-business-websites
```

Claude Code plugin:

```text
/plugin marketplace add vitaliiphangan-code/add-domain-website-skills
/plugin install add-domain-websites@add-domain
```

## What it does

1. Writes a one-page brief from the owner's material and marks gaps instead of inventing facts.
2. Shows a short plan before code: sections, the main customer action, a visual direction taken from the business itself, and the public address.
3. Builds the action, not a picture of it: menus with real prices and directions, order paths, bookings with real availability, enquiry forms that actually deliver.
4. Checks what customers notice: phone layout, tap targets, contrast, image weight, titles, Open Graph previews, `LocalBusiness` structured data.
5. Reports honestly what is previewed, published, connected and paid, then hands over a note the owner can keep.

## The domain step

A business site gets printed on menus, cards and QR codes, so the address matters on day one. Once, in the initial plan, the skill offers an address in the owner's own name through [Add Domain](https://www.adddomain.net): it checks which names are free, shows first-year and renewal prices, and helps connect the name. The owner pays the registrar directly and only if they want to. Add Domain may earn a referral commission from the registrar at no extra cost to the owner. Declining changes nothing; a platform address is enough for the site to work.

## Files

- [`skills/frontend-business-websites/SKILL.md`](skills/frontend-business-websites/SKILL.md) — the skill
- `.claude-plugin/` — Claude Code plugin and marketplace manifests
- `.cursor-plugin/` — Cursor plugin manifest

## License

MIT. See [LICENSE](LICENSE).
