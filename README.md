# rekajs
SPA application core elements. This packages are required by rekamy/Generator package


# Installation
`npm i rekajs`

# How to use
```
import { api, bloc, store } from 'rekajs'

api.get('my-endpoint')

if( bloc.hasApi() ) bloc.api.get()

if( bloc.hasStore() ) bloc.store.save(data)

auth.authenticate({username: 'username', password: 'password', token: 'token'})

if( auth.loggedIn() ) {
    // authorized method
} else {
    auth.redirect()
}

```

## Components
* api
* store
* auth
* bloc
* rtc (Real-time communicator)
* widget (alert, notifier)
* vue-component