---
layout: default
---

# Policy

Thank you for helping us keep {{ company_name }} users safe! We ask that all researchers:

*   Make every effort to avoid privacy violations, degradation of user experience, disruption to production systems, and destruction of data during security testing;
*   Perform research only within the scope set out below;
*   Use the identified communication channels to report vulnerability information to us;
*   Report vulnerabilities as soon as you discover them;
*   Keep information about any vulnerabilities you’ve discovered confidential between yourself and {{ company_name }} until we’ve had 90 days to resolve the issue.

If you follow these guidelines when reporting an issue to us, we commit to:

*   Not pursue or support any legal action related to your research;
*   Work with you to understand and resolve the issue quickly (including an initial confirmation of your report within 72 hours of submission).

## Scope

### In-scope

* [https://example.com](https://example.com)
* [https://example.co](https://example.co)

### Out of Scope

In the interest of the safety of our users, staff, the Internet at large and you as a security researcher, the following test types are excluded from scope:

* Findings from physical testing such as office access (e.g. open doors, tailgating).
* Findings derived primarily from social engineering (e.g. phishing, vishing).
* Findings from applications or systems not listed in the ‘Scope’ section.
* Vulnerability reports with video only PoCs.
* Reports that state that software is out of date/vulnerable without a proof of concept.
* Highly speculative reports about theoretical damage. Be concrete.
* Vulnerabilities as reported by automated tools without additional analysis as to how they're an issue.
* Reports from automated web vulnerability scanners (Acunetix, Vega, etc.) that have not been validated.
* Recently disclosed 0day vulnerabilities. We need time to patch our systems just like everyone else - please give us 30 days before reporting these types of issues.
* Issues in third-party services should be reported to the respective team. Please take a look at the "Third-party Services" section for more information.

The following issue types are excluded from scope:

* Network level Denial of Service (DoS/DDoS) vulnerabilities.
* Low severity issues that can be detected with tools such as [Hardenize](https://www.hardenize.com/) and [SecurityHeaders.io](https://securityheaders.io/).
* XSS issues that affect only [outdated browsers](http://outdatedbrowser.com/).
* Content injection issues.
* Cross-site Request Forgery (CSRF) with minimal security implications (Logout CSRF, etc.).
* Missing cookie flags on non-security-sensitive cookies.
* UI and UX bugs and spelling mistakes.
* [CSV injection](https://www.contextis.com/blog/comma-separated-vulnerabilities).
* [401 injection](https://security.stackexchange.com/a/135534).
* Stack traces that disclose information. We are open source so most of this information is already out there.
* Host header issues without an accompanying proof-of-concept demonstrating vulnerability.
* Open ports without an accompanying proof-of-concept demonstrating vulnerability.
* Banner grabbing issues (figuring out what web server we use, etc.).

## Reporting

If you believe you’ve found a security vulnerability in one of our products or platforms, please send it to us via our [report form]({{ site.baseurl }}/report).

Please provide detailed reports with reproducible steps. If a report is not detailed enough to reproduce the issue, it will not be eligible for a bounty.

## Rewards

If you are the first to report an issue, and we make a code or configuration change based on the issue, we will award you:

| Severity | CVSS       | Example       | Award |
|:---------|:----------:|:--------------|:------|
| Critical | 9.0 - 10.0 | RCE           | $500  |
| High     | 7.0 - 8.9  | SQLi          | $100  |
| Medium   | 4.0 - 6.9  | Reflected XSS | $50   |
| Low      | 0.1 - 3.9  | Self-XSS      | $10   |
| None     | 0          | ¯\\\_(ツ)\_/¯ | ¯\\\_(ツ)\_/¯ |

## Third-party Services

{{ company_name }} uses the following third-party services. If you discover an issue make sure to report it to the service's security team.

<!-- Insert list of third-party services here. -->