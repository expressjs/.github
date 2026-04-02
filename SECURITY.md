# Security Policies and Procedures

This document outlines security procedures and general policies for the Express
project.

  * [Reporting a Bug or Security Vulnerability](#reporting-a-bug-or-security-vulnerability)
  * [Disclosure Policy](#disclosure-policy)
  * [Comments on this Policy](#comments-on-this-policy)
  * [The Express Threat Model](#the-express-threat-model)

## Reporting a Bug or Security Vulnerability  

> [!IMPORTANT]
> Before reporting a vulnerability, please review the [Express Threat Model](#the-express-threat-model) to check if the issue falls within Express's security scope.

The Express team and community take all security vulnerabilities seriously. 
Thank you for improving the security of Express and related projects. 
We appreciate your efforts in responsible disclosure and will make every effort 
to acknowledge your contributions.  

A [Security triage team member](https://github.com/expressjs/security-wg#security-triage-team-expressjssecurity-triage) 
or [the repo captain](https://github.com/expressjs/discussions/blob/master/docs/contributing/captains_and_committers.md) 
will acknowledge your report as soon as possible. 
These timelines may extend when our triage 
volunteers are away on holiday, particularly at the end of the year.

After the initial reply to your report, the security team will
endeavor to keep you informed of the progress towards a fix and full
announcement, and may ask for additional information or guidance.

> [!NOTE]  
> You can find more information about our process in [this guide](https://github.com/expressjs/security-wg/blob/main/docs/incident_response_plan.md)


### Reporting Security Bugs via GitHub Security Advisory (Preferred)  

The preferred way to report security vulnerabilities is through 
[GitHub Security Advisories](https://github.com/advisories). 
This allows us to collaborate on a fix while maintaining the 
confidentiality of the report.  

To report a vulnerability
([docs](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)):  
1. Visit the **Security** tab of the affected repository on GitHub.  
2. Click **Report a vulnerability** and follow the provided steps.  

This process applies to any repositories within the Express ecosystem. 
If you are unsure whether a repository falls under this policy, 
use the express repository

### Reporting via Email  

We don't accept reports via emails anymore.

### Third-Party Modules  

If the security issue pertains to a third-party module that is not directly maintained within the Express ecosystem, please report it to the maintainers of that module.  

## Disclosure Policy

When the security team receives a security bug report, they will assign it to a
primary handler. This person will coordinate the fix and release process,
involving the following steps:

  * Confirm the problem and determine the affected versions.
  * Audit code to find any potential similar problems.
  * Prepare fixes for all releases still under maintenance. These fixes will be
    released as fast as possible to npm.

## Comments on this Policy

If you have suggestions on how this process could be improved please submit a
pull request.

## The Express Threat Model

The Express threat model defines the boundaries of what the framework considers its security responsibility. It establishes which elements are trusted (such as the developer, the runtime environment, and application code) versus untrusted (such as data from network connections). Issues arising from trusted elements are considered out of scope, while Express is responsible for safely handling untrusted data.

Many commonly reported concerns fall outside Express's security scope and are the responsibility of the application developer. Such as prototype pollution from unsanitized user input, misconfigured static file serving, or issues in third-party dependencies.

For complete details, see the [Express Threat Model](https://github.com/expressjs/security-wg/blob/main/docs/ThreatModel.md).
