# Security Policies and Procedures

This document outlines security procedures and general policies for the Express
project.

  * [Reporting a Bug](#reporting-a-bug)
  * [Disclosure Policy](#disclosure-policy)
  * [Comments on this Policy](#comments-on-this-policy)

## Reporting a Bug

The Express team and community take all security bugs in Express seriously.
Thank you for improving the security of Express. We appreciate your efforts and
responsible disclosure and will make every effort to acknowledge your
contributions.

Report security bugs by emailing `express-security@lists.openjsf.org`.

To ensure the timely response to your report, please ensure that the entirety
of the report is contained within the email body and not solely behind a web
link or an attachment.

A [Security triage team member](https://github.com/expressjs/security-wg#security-triage-team) 
or [the repo captain](https://github.com/expressjs/express/blob/master/Contributing.md#active-projects-and-captains) 
will acknowledge your email as soon as possible. 
These timelines may extend when our triage 
volunteers are away on holiday, particularly at the end of the year.

After the initial reply to your report, the security team will
endeavor to keep you informed of the progress towards a fix and full
announcement, and may ask for additional information or guidance.

> [!NOTE]  
> You can find more information about our process in [this guide](https://github.com/expressjs/security-wg/blob/main/docs/handle_security_reports.md)

Report security bugs in third-party modules to the person or team maintaining
the module.

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
