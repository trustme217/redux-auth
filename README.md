# Features:

* Supports isomorphic / universal / server-side rendering
* [OAuth2 authentication components](#oauthsigninbutton)
* Email authentication components, including:
  * [User registration](#emailsignupform)
  * [Password resets](#requestpasswordresetform)
  * [Email sign in](#emailsigninform)
* Seamless integration with the [devise token auth][dta] Rails gem.
* Includes the following themes:
  * [Material UI][material-ui]
  * [React Bootstrap][react-bootstrap]
  * A plain theme that you can style from scratch
* Support for [multiple user types](#multiple-user-types)
* **coming soon** React Native support
* **coming soon** I18n support
* **coming soon** Can be configured to work with any API

# Installation

Only npm is currently supported.

~~~sh
npm install redux-auth --save
~~~

If you want to use the [Material UI][material-ui] or [Bootstrap][react-bootstrap] themes, you will need to install those libraries as well.

~~~sh
# install material ui
npm install material-ui --save

# or bootstrap
npm install react-bootstrap --save
~~~

Material UI uses inline styles so no further configuration is needed. But with the bootstrap theme, the CSS will also need to be included. Read more at the [React Bootstrap][react-bootstrap] project page.

You must also install and use a json loader

--
