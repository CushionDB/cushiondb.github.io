## API
--------

# Store API

#### store.getAll()
```js

```
#### store.set(document)
```js

```
#### store.get(documentID)

#### store.update(documentID, attributes)

#### store.find(fieldName, fieldValue)

#### store.delete(documentID)

#### store.destroy()

#### store.deleteAll()


# Account API

#### account.isSignedIn()

#### account.signUp( { username, password } )

#### signIn({username, password})

#### signOut()

#### changePassword( username, newPassword )

#### destroy(username)

#### changeUsername( {curUsername, password, newUsername} )

# Cushion Worker API

#### cushionWorker.addPushEvent(eventID, eventCallback)

#### cushionWorker.addMessageEvent(eventID, eventCallback)

#### cushionWorker.addSyncEvent(eventID, eventCallback)

#### cushoinWorker.removePushEvent(eventID)
