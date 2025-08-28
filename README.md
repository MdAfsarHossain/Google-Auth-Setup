# GOOGLE AUTH SETUP

# [Passport](https://www.passportjs.org)

# [Passport Package](https://www.passportjs.org/packages)

# [Passport Local](https://www.passportjs.org/packages/passport-local)

# [Passport OAuth](https://www.passportjs.org/packages/passport-oauth2)

In `app.ts` file

```js
app.use(
  expressSession({
    secret: envVars.EXPRESS_SESSION_SECRET,
    resave: false,
    saveUninitialized: false,
  })
);
app.use(passport.initialize());
app.use(passport.session());
```
