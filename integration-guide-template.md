# PagerDuty + RoleUp Integration Benefits

- Track all your team accounts in one place with simple OAuth-based setup, no SAML, LDAP or identity providers
- Streamline onboarding and offboarding of team members with just a few clicks. Users can even self-onboard by providing key account details.

# How it Works
- Once linked with RoleUp, new users can be added to PagerDuty through the RoleUp UI while they are simultaneously added to other services during onboarding
- If users are added directly within PagerDuty, those changes will be detected and synced back to RoleUp for tracking.
- When the time comes to offboard a team member, a single click in the RoleUp interface will disable or remove all accounts associated with that user.
- Offboarding PagerDuty users can have effects on on any open incidents assigned to them. To configure these effects [https://support.pagerduty.com/docs/offboarding#section-configure-offboarding-settings](read more about offboarding actions in PagerDuty).

# Requirements
- PagerDuty integrations require an Admin base role for account authorization. If you do not have this role, please reach out to an Admin or Account Owner within your organization to configure the integration.

# Support
If you need help with this integration, please contact [support@roleup.io](mailto:support@roleup.io). 

Additionally, here is some relevant PagerDuty documentation on user management. 
- [https://support.pagerduty.com/docs/users](Adding and Removing Users)
- [https://support.pagerduty.com/docs/user-roles](User Roles)
- [https://support.pagerduty.com/docs/advanced-permissions](Advanced Permissions)
- [https://support.pagerduty.com/docs/teams](Teams)
- [https://support.pagerduty.com/docs/offboarding](Offboarding Users)

# Integration Walkthrough
## In RoleUp

1. Create a user acocunt and organization in RoleUp if you have not already done so.
2. Add the PagerDuty integration from the **Integrations** section of RoleUp, or by going [here](https://app.roleup.io/orgs/_/add-integration?integration=pagerduty). The only required field is your PagerDuty subdomain, visible in your PagerDuty URL like so: **https://{subdomain}.pagerduty.com**
3. Click **Add** to add the PagerDuty integration
4. All of your users and teams within PagerDuty will automatically sync into RoleUp when the integration is created, and will continue to sync periodically afterwards.
5. In the **Identities** section of RoleUp, the PagerDuty users will be automatically merged into Identities with accounts that share the same email.
6. If you have more than one PagerDuty subdomain to add, you can repeat the above process for any additional subdomains.

### Notes
- PagerDuty team and role management is not currently supported via RoleUp, but will be added in the future. 

# How to Uninstall

1. Go to the **Integrations** section of RoleUp [here](https://app.roleup.io/orgs/_/integrations) and look for the PagerDuty integration you wish to uninstall.
2. Click the **Edit** button
3. At the bottom of the integration configuration page, click the button that says **Remove Permenantly**
