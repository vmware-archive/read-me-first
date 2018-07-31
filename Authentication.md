__Overview__ 

To improve security and diminish delays in access, the new Pivotal Org is now SAML authenticated.  What does this mean? In the vast majority of cases, you should not see any significant change to how you have interacted with your past orgs.  The biggest changes you will see depend on how you are trying to access the system.

__Authenticating through the UI__

Initially, all users will need to authenticate their account through the GitHub UI by having an active Okta session in their browser.  Once you have done this, you will need to re-authenticate every 24 hours, as the Okta session needs to be active in your browser to use GitHub’s UI.

__Authenticating through the command line__

Day to day, we know many of you operate with GitHub solely through the command line, and fortunately very little will change with how this works.  If you are not currently aware how to generate a Personal Access Token or 

The major difference is,  now need to initially authorize your Personal Access token for the /Pivotal org (you may create a new one, or authorize an existing key for the new, SAML authenticated org).  Instructions on how to authorize a Personal Access token can be found here: [Authorizing a personal access token for use with a SAML single sign-on organization](https://help.github.com/articles/authorizing-a-personal-access-token-for-use-with-a-saml-single-sign-on-organization/).

For more information, including how to generate a Personal Access token, please see [GitHub’s SAML Authentication Guide](https://help.github.com/articles/about-authentication-with-saml-single-sign-on/). 
