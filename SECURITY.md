# Reporting a Security Issue

## Please do not report security issues in a public issue

Once a vulnerability is filed as a public issue, anyone can read it before a fix ships — including anyone who might exploit it. That puts other ODE+ users at risk.

**Use one of these private channels instead:**

1. **GitHub private vulnerability reporting** — open [*Report a vulnerability*](https://github.com/orthogonalgroup/odeplus/security/advisories/new) on this repository's Security tab. The report stays visible only to you and the ODE+ team.
2. **Email** — <orthogonalpub@outlook.com>, with `[Security]` in the subject line.

## What to include

- The class of issue, and which feature or page is affected
- Steps to reproduce — enough for us to observe the problem independently
- Your assessment of the impact: what data becomes reachable, what actions become possible
- A proof of concept or relevant log excerpts, if you have them

## What happens next

1. We confirm receipt of your report.
2. We reproduce it and assess the impact, and may come back to you for details.
3. We ship a fix and tell you when it lands.
4. If you would like credit, we will name you in the advisory. Staying anonymous is equally fine.

Please hold off on publicly disclosing the details until a fix has shipped.

## What is not a security issue

Errors, incorrect results, and pages failing to load do not by themselves expose data or bypass permissions. File those as a regular [bug report](https://github.com/orthogonalgroup/odeplus/issues/new?template=bug_report.yml) — the public process will get you visible progress faster.
