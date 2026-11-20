# IAM Labs

Hands-on IAM labs with Microsoft Entra ID, Okta, and Active Directory.

## Microsoft Entra ID — Dynamic Group Membership

I built a dynamic group rule that adds nurses to the Clinical All Nurses group based on their company and job title. I tested a role change by updating Maria’s job title from RN to HR Specialist and verified that Entra ID automatically removed her from the group.

[Watch the Loom demo](https://www.loom.com/share/9a0bd42239214565afc45af0c5b1bfbe)

## Okta SAML SSO with Salesforce

I configured Salesforce to use Okta as its identity provider and verified that an assigned test user could sign in through Okta.

[Watch the SAML SSO demo](https://www.loom.com/share/6d7ae491d53b49c7b30340d07084a316)

## Microsoft Entra ID — Conditional Access to Require MFA

I configured a Conditional Access policy to require MFA and tested it in report-only mode before enabling it.

[Watch the Conditional Access demo](https://www.loom.com/share/fe12e8d96cf548229df045c14521ef5e)

## Microsoft Entra ID — Privileged Identity Management (PIM)

I configured an eligible assignment for the Privileged Role Administrator role. Activation required MFA, justification, and approval, with a four-hour maximum.

[Watch the PIM lab demo](https://www.loom.com/share/1bc949a2df324dc3b7391430d259fa18)
