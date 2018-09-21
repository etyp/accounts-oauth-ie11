# Meteor 1.8 accounts-oauth IE11 issue
This was created using the following steps:

1. `meteor create --full accounts-oauth-ie11`
2. `meteor update --release 1.8-rc.16`
3. `meteor add accounts-google@1.3.2-rc18.16`

When running the app and opening in IE11, you'll get the following errors:

```
Syntax error
accounts-oauth.js (36,40)

Unable to get property 'registerService' of undefined or null reference
accounts-google.js (51,1)
```
