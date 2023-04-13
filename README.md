# Introduction

A react project using authentication.
It also uses react-router-dom with implementations of loader and action events.

# Bug fix

In util/auth.js I have inserted the following line to the checkAuthLoader function

There was a problem with editing and making new events. It looks like this has fixed it.

```javascript
//just inseted this on by chance. Not sure if it should stay in here.
return token;
```
