# @reiwa/errors

The set of Firebase Functions status codes.

```
$ yarn add @reiwa/errors
```

## Usage

https://firebase.google.com/docs/functions/locations?hl=en#selecting-regions_firestore-storage

```ts
import { https } from 'firebase-functions'
import { NOT_FOUND } from '@reiwa/errors'

throw new https.HttpsError(NOT_FOUND, 'No data found')
```
