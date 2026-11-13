# Contributing

Thanks for wanting to help. This repository is the public showcase page for Brain Box, and it is deliberately small.
That keeps it easy to review and safe to publish.

## What is welcome

- Typos, unclear wording, and ways to make the text shorter and plainer.
- Accessibility fixes: contrast, focus order, keyboard use, screen reader labels, motion.
- Layout bugs on phones, tablets or unusual browsers.
- Factual corrections, with a link or a quote that shows what is wrong.

## What is out of scope

- Changes to the Brain itself. It is developed in a separate, private repository, so changes to it cannot be made here.
- New sections that promise features the Brain does not have yet.
- Anything that adds tracking, cookies, adverts, fonts or scripts from other sites, or a build tool.
- Screenshots or recordings of a real dashboard.

## Ground rules (these protect the project)

1. **Nothing private, ever.** No IP addresses, hostnames, ports, tokens, passwords, webhook URLs, SSH details, container
   names from a real system, or copied journal or dashboard text. If you are not sure, leave it out.
2. **Be honest.** Say what the Brain does today. Mark ideas as ideas. Keep the "honest bit" honest.
3. **Stay calm and readable.** Keep the display modes working, keep text short, and respect reduced-motion settings.
4. **Stay static.** One HTML file, no build step, no outside scripts. If a change needs a build tool, open an issue first.
5. **Change one thing at a time.** Small pull requests are easier to review and easier to undo.

## How to propose a change

1. Open an issue first for anything bigger than a typo. Use one of the issue forms.
2. Fork the repository and create a branch with a short name, for example `fix/contrast-footer`.
3. Edit `index.html`. Preview it locally (see the README).
4. Run the privacy check from the README. It must print nothing.
5. Check the page at phone width and with the three display modes (Readable, High contrast, Theme).
6. Open a pull request and fill in the template.

A maintainer will review it, may ask for changes, and decides what is published. Nothing reaches the live page
until a maintainer merges to `main`.

## Style notes

- Language: British English.
- Reading level: plain and short. Prefer a clear short sentence over a clever long one.
- Keep every interactive control reachable by keyboard and labelled for screen readers.
- Colours come from the CSS variables at the top of the file, so a theme change stays in one place.

## Commit messages

Use a short summary line that says what changed and why, for example: `Raise footer text contrast in light theme`.

## Reporting a security or privacy problem

Please do not open a public issue. See [SECURITY.md](SECURITY.md).

## Conduct

By taking part you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
