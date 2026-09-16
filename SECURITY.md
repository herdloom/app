# Security

Thank you for looking. Shepherd runs on a developer's machine, works on their
source code, and drives agents that can change files, so security reports are
taken seriously.

## Reporting a vulnerability

Please report privately, not in a public issue.

- Use [GitHub's private advisory form](../../security/advisories/new) (preferred), or
- email **[SECURITY EMAIL]** with "Shepherd security" in the subject.

Include what you found, how to reproduce it, what an attacker could do with it,
and the app version. A proof of concept helps; a working exploit is not needed.

### What to expect

| | |
|---|---|
| First reply | within 3 working days |
| Assessment | within 10 working days |
| Fix for a confirmed issue | in the next beta build, or sooner if serious |

You will be credited in the release notes when a report leads to a fix, unless
you would rather not be.

## In scope

- The Shepherd application and the local service it runs
- The way Shepherd stores credentials, tokens and agent output on disk
- The way Shepherd isolates work in git worktrees and branches
- Anything that lets one project's work reach another's, or reach the main checkout unasked

## Out of scope

- The coding agent CLIs themselves, and the models behind them: report those to their authors
- Issues that need an attacker to already have full access to the machine and the user's account
- Missing hardening that has no demonstrated impact
- Anything in a repository you do not own or have permission to test against

## Please do not

- Test against machines or repositories that are not yours
- Run denial of service, spam, or social engineering against anyone
- Access, change or keep other people's data

## Handling your report

Reports are read by the author. They are not shared with anyone else, and the
details stay private until a fix is out.
