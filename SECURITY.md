# Security Policy

## Reporting a vulnerability

Please report security vulnerabilities using [GitHub's private vulnerability
reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
on the affected repository. Don't open a public issue for a vulnerability.

Maintainers will acknowledge a report within 2 weeks. An acknowledgement is
enough; it isn't a commitment to ship a fix within that time.

If you don't receive an acknowledgement in that time, or you need to reach
Django Commons directly, email
[django-commons-admin@googlegroups.com](mailto:django-commons-admin@googlegroups.com).
The admin team backs up project maintainers on security reports and can take over
a project to fix an issue if the maintainers can't be reached.

## Reporting Guidelines

These guidelines are taken from [Django's security
policy](https://docs.djangoproject.com/en/dev/internals/security/).

Your initial report should give the maintainers enough to make a triage
decision, no more. It should include:

- A brief description of the issue and where it occurs.
- A minimal, working proof of concept. Privately share a minimal project or code
  snippet with clear instructions to set it up, run it and reproduce the issue.
  Don't attach screenshots of code.
- The versions of the project, Python and Django you tested against.
- Optionally, a minimal patch with the mitigation for the issue.

Please don't include severity scores (CVSS or otherwise), lengthy background
sections, or a determination of whether the issue is a vulnerability. The
maintainers will make those assessments. If the report is confirmed, they will
follow up and welcome more detail.

For a report to be valid:

- **Use supported versions of dependencies.** The issue must be reproducible
  when all relevant dependencies, including Python, are at supported versions.
  Issues that only occur on an end-of-life Python version aren't valid.
- **Code under test must feasibly exist in a Django project.** The proof of
  concept must plausibly occur in a production-grade Django application,
  following standard development practices. Issues that depend on calling
  private or undocumented functions in an unsafe way aren't valid.

## Supported versions

Security fixes are provided for the versions each project documents as
supported. This varies project to project, so check the project's own
documentation.

## Safe harbor

Django Commons will not pursue legal action against researchers who report a
vulnerability in good faith, make a reasonable effort to avoid privacy
violations and service disruption, and give us a reasonable time to respond
before any public disclosure.
