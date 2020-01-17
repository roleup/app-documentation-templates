# PagerDuty + RoleUp Integration Benefits

- Track all your team accounts in one place with simple OAuth-based setup, no SAML, LDAP or identity providers
- Streamline onboarding and offboarding of team members with just a few clicks. Users can even self-onboard by providing key account details.

# How it Works
- Once linked with RoleUp, new team members can be added to PagerDuty through the RoleUp UI while they are simultaneously added to other services during onboarding
- If users are added directly within PagerDuty, those changes will be detected and synced back to RoleUp for tracking.
- When the time comes to offboard a team member, a single click in the RoleUp interface will disable or remove all accounts associated with that user.

# Requirements
- PagerDuty integrations require an Admin base role for account authorization. If you do not have this role, please reach out to an Admin or Account Owner within your organization to configure the integration.

# Support
If you need help with this integration, please contact [support@roleup.io](mailto:support@roleup.io). 

# Integration Walkthrough
## In RoleUp

1. Create a user acocunt and organization in RoleUp if you have not already done so.
2. Add the PagerDuty integration from the **Integrations** section of RoleUp, or by going [here](https://app.roleup.io/orgs/_/add-integration?integration=pagerduty). The only required field is your PagerDuty subdomain, visible in your PagerDuty URL like so: **https://{subdomain}.pagerduty.com**
3. Click **Add** to add the PagerDuty integration
3. All of your users and teams within PagerDuty will automatically sync into RoleUp when the integration is created, and will continue to sync periodically afterwards.
4. In the **Identities** section of RoleUp, the PagerDuty users will be automatically merged into Identities with accounts that share the same email.
5. If you have more than one PagerDuty subdomain to add, you can repeat the above process for any additional subdomains.

# How to Uninstall

1. Go to the **Integrations** section of RoleUp [here](https://app.roleup.io/orgs/_/integrations) and look for the PagerDuty integration you wish to uninstall.
2. Click the **Edit** button
3. At the bottom of the integration configuration page, click the button that says **Remove Permenantly**
