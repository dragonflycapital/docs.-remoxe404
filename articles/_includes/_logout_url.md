<!-- markdownlint-disable MD002 MD041 -->

### Configure Logout URLs

A logout URL is a URL in your application that Auth0 can return to after the user has been logged out of the authorization server. This is specified in the `returnTo` query parameter. The logout URL for your app must be added to the **Allowed Logout URLs** field in your <a href="${manage_url}/#/applications" target="_blank" rel="noreferrer">Application Settings</a>. If this field is not set, users will be unable to log out from the application and will get an error.

<% if (typeof(returnTo) !== "undefined") { %>
  ::: note
  If you are following along with the sample project you downloaded from the top of this page, the logout URL you need to add to the **Allowed Logout URLs** field is `${returnTo}`.
  :::
<% } %>
