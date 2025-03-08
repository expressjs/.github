# Security Policies and Procedures

This document outlines security procedures and general policies for the Express
project.

  * [Reporting a Bug or Security Vulnerability](#reporting-a-bug-or-security-vulnerability)
  * [Disclosure Policy](#disclosure-policy)
  * [Comments on this Policy](#comments-on-this-policy)

## Reporting a Bug or Security Vulnerability  

The Express team and community take all security vulnerabilities seriously. 
Thank you for improving the security of Express and related projects. 
We appreciate your efforts in responsible disclosure and will make every effort 
to acknowledge your contributions.  

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
feel free to reach out via email.  

### Reporting via Email  

If you prefer, you can also report security issues by emailing `express-security@lists.openjsf.org`.  

To ensure a timely response, please include all relevant details directly in the email body rather than linking to external sources or attaching files.  

The lead maintainer will acknowledge your email within 48 hours and provide an initial response outlining the next steps. The security team will keep you updated on the progress and may request additional details.  

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
