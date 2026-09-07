# Reporting a security problem

Hands runs on your own machine, with your logins, and drives a real computer. A bug in it can
therefore matter more than a bug in a website. If you find one, we want to hear about it before
anyone else does.

**Please do not open a public issue.** Email **hello@tryhands.com** with `SECURITY` in the subject.
Include what you did, what happened, and the build you were on — the version is in the app's About
window.

You will get a reply from a person within three working days. If we agree it is a problem, we will
tell you what we are doing about it and when, and we will credit you in the release notes unless you
would rather we did not.

## In scope

Anything in a shipped Hands build, and the services it talks to:

- `accounts.tryhands.com` — sign-in
- `connect.tryhands.com` — the connector broker
- `models.tryhands.com` — the model broker and credit
- `tryhands.com` — the website

## Out of scope

- Reports from automated scanners with no working proof
- Missing headers or TLS configuration with no demonstrated impact
- Anything requiring physical access to an already-unlocked machine
- Social engineering of us or our users

## What we ask

Test against your own installation and your own accounts. Do not access anyone else's data, degrade
the service for others, or run automated load against the brokers. If you follow that, we will not
pursue you.

There is no bug bounty programme yet. We will say so here when there is.
