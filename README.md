resources:

https://scotch.io/tutorials/easy-node-authentication-facebook

TODO:

facebook auth works but the return user object does not have info of user
its mostly undefined

- facebook auth scope
https://developers.facebook.com/docs/facebook-login/permissions/
https://developers.facebook.com/docs/graph-api/reference/user


-> solved by:
    - putting the app in public mode

    - following new technique, explicitly specifying fields
        https://stackoverflow.com/questions/31279066/passport-facebook-not-providing-email-even-if-it-is-in-scope