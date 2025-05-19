# Login banner MFA factor
This is a Moodle plugin which adds a MFA factor to display a login banner.

Originally included in Catalyst's tool_mfa plugin, it has now been split off into its own repository as tool_mfa was added to Moodle core in 4.3 as part of https://tracker.moodle.org/browse/MDL-78509.

It was taken at this commit: https://github.com/catalyst/moodle-tool_mfa/tree/7fed04b24c3857e155fb2b29b70e04d6f2d42aff/factor/loginbanner

# How does it work

This factor allows for display of a policy which forces users to read and accept a policy on every login. This is more flexible than the Moodle policy tool, which is built for one time acceptance. To set the message, a custom language pack should be used to override factor_loginbanner/policytext. This means that it can be replaced with an arbitrary set of HTML to display to the users. This factor should be used with a weight of 0 if you wish it to be an additional layer over the top of the MFA flow, without contributing any weight.


# Branches

| Branch            | Version     |
|-------------------|-------------|
| MOODLE_403_STABLE | Moodle 4.3+ |

# Contributing and support

Issues, and pull requests using github are welcome and encouraged!

https://github.com/catalyst/moodle-factor_loginbanner/issues

If you would like commercial support or would like to sponsor additional improvements to this plugin please contact us:

https://www.catalyst-au.net/contact-us
