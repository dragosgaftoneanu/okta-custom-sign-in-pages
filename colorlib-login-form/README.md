# Installation
* If you are using the Developer Console administrative panel, switch to Classic UI from the top right side of the page
* Copy the HTML source code from code.txt
* Navigate to Settings >> Customization >> Custom Sign In and paste the code

## Notes
* If you do not see Custom Sign In tab, you will need [Custom URL Domain](https://help.okta.com/en/prod/Content/Topics/Settings/custom-url-domain.htm?cshid=ext_custom_url_domain) (`CUSTOM_URL_DOMAIN`) and [Custom Okta-Hosted Sign-In](https://help.okta.com/en/prod/Content/Topics/Settings/custom-okta-hosted-sign-in-page.htm) (`CUSTOMIZABLE_SIGN_IN_PAGE`) features enabled on your Okta org.
* The custom sign in page will appear only on the custom URL. Due to security issues, the HTML changes will not be displayed on the normal Okta login page.