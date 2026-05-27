# LibreHTX 2026 Design.md

## Purpose

LibreHTX 2026 is a Houston meetup landing site for free software, open source, digital rights, privacy, and practical collaboration.

The design should feel welcoming, credible, modern, and easy to scan on mobile.

## Audience

Primary audiences:
- People new to free software or open source.
- Local technologists.
- Privacy and digital rights advocates.
- Community members who want to understand the event quickly.

Secondary audiences:
- Search engines.
- AI assistants and other LLM-based tools that summarize or answer questions from the site.

## Brand voice

Tone:
- Clear.
- Welcoming.
- Calm.
- Specific.
- Non-technical when possible.

Avoid:
- Hype.
- Gatekeeping.
- Jargon without explanation.
- Overly formal nonprofit language.
- Overclaiming organizational affiliation.

## Visual identity

Design goals:
- Readable.
- Mobile-first.
- Lightweight.
- Community-oriented.
- Friendly but not playful.

Visual style:
- Clean headings.
- Strong spacing.
- Simple navigation.
- Minimal decoration.
- One clear call to action per page when possible.

## Typography

Use a system font stack for speed, compatibility, and readability.

This keeps the site fast to load, avoids layout shifts, and makes the text feel native on each device.

Suggested rule:
- Use one sans-serif system stack across the site.
- Keep body text comfortable to read.
- Preserve a clear heading hierarchy.
- Avoid decorative or novelty fonts.

Typography intent:
- Professional.
- Clean.
- Easy to scan.
- Mobile-friendly.

## Color tokens

Use an accessible, high-contrast palette.

Suggested tokens:

```yml
colors:
  background: "#ffffff"
  surface: "#f6f8fa"
  text: "#1f2328"
  muted_text: "#57606a"
  border: "#d0d7de"
  primary: "#0969da"
  primary_hover: "#0550ae"
  accent: "#8250df"
  success: "#1a7f37"
  warning: "#9a6700"
  danger: "#cf222e"
