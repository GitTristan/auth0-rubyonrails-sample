# Auth0 + Ruby on Rails WebApp Seed + Samples
This project goal is to help integrating Auth0 capabilities in your Ruby on Rails application.

You can learn more about the seed project and samples in the [Auth0 Rails quickstart](https://auth0.com/docs/quickstart/webapp/rails).

## Contents
### 00 - WebApp Seed
Learn how to setup your application integrating Auth0 libraries and tools.

### 01 - Login
Learn how to add login capabilities to your Rails application using the Auth0 Lock widget and the OmniAuth authentication system.

### 02 - Custom Login
Learn how to add login and signup capabilities to your Rails application using the Auth0 Ruby SDK.

### 03 - Session Handling
Learn how to store session data and cleanup the session on logout.

### 04 - User Profile
Learn how to retrieve an Auth0 user’s profile in a Rails application using OmniAuth.

### 05 - Linking Accounts
Learn how to link/unlink different Auth0 users accounts using Lock, OmniAuth, and the Auth0 Ruby SDK.

### 07 - Authorization
Learn how to add Authorization based on the user role for a resource in your Rails app.

### 08 - MFA
Learn how to add Multifactor Authentication to your Auth0 authentication flow in a Rails app.

### 09 - Customizing Lock
Learn how to customize the Lock widget to match the look and feel of your app.

## Used Libraries
* [Auth0 Lock](https://github.com/auth0/lock)
* [Auth0 Ruby SDK](https://github.com/auth0/ruby-auth0)
* [OmniAuth](https://github.com/intridea/omniauth)
* [OmniAuth Auth0 Strategy](https://github.com/auth0/omniauth-auth0)
* [OmniAuth Oauth2](https://github.com/intridea/omniauth-oauth2)

### Troubleshooting issues

1) If you receive the following error, on Mac:

```
An error occurred while installing pg (0.19.0), and Bundler cannot continue.
Make sure that `gem install pg -v '0.19.0'` succeeds before bundling.
```

Try running the following commands:

1. `brew update`
2. `brew install postgresql`
3. `gem install pg`
4. Then go back to the project and run: `bundle install`

2) If you receive the following error, on Mac:

```
An error occurred while installing nokogiri (1.7.0.1), and Bundler cannot
continue.
Make sure that `gem install nokogiri -v '1.7.0.1'` succeeds before bundling.
```

Simply run:

```
gem install nokogiri -- --use-system-libraries=true --with-xml2-include=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.12.sdk/usr/include/libxml2/
```

More info, [here](http://stackoverflow.com/questions/24251494/nokogiri-gem-installation-error).
