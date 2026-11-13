# Security policy

## What this repository is

A static web page with no server, no database, no login and no stored user data. Its only script saves display preferences
(readable text, contrast, theme) in the visitor's own browser.

## What to report

- Private information that should not be public: an address, hostname, token, webhook URL, or text copied from a real system.
- A script or link on the page that does something unexpected.
- Anything that could mislead visitors into thinking they are on a real, live Brain Box dashboard.

## How to report

Use GitHub's private reporting: open the **Security** tab of this repository and choose **Report a vulnerability**.
Please do not post details in a public issue or pull request.

Include what you found, where, and how to see it. Please do not test against anyone's systems other than your own.

## What to expect

You will get an acknowledgement as soon as the maintainer can, usually within a few days. If something private has been
published, the first step is to remove it from the page, then to look at whether anything needs to be rotated or changed
elsewhere.

## Supported versions

Only the current `main` branch (the live page) is supported.
