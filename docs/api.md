# API 
--------

## Store API

#### store.getAll()

```js
store.getAll().then( docs => {
  docs.forEach( doc => {
  // process each document
  });
});

```
#### store.set(document)
```js
store.set(doc).then(id => {
  // 
});
```
#### store.get(documentID)
```js
store.get(documentID).then( doc => {
  // 
});
```

#### store.update(documentID, attributes)
```js
attributes = { newColum: 'new value' };

store.update(documentID, attributes).then( id => {
  // 
});

```

#### store.find(fieldName, fieldValue)

```js
fieldName = 'Todos';
fieldValue = 'Go Hiking';

store.find(fieldName, fieldValue).then( docs => {
  // 
});

```

#### store.delete(documentID)
```js

```

#### store.destroy()
```js

```

#### store.deleteAll()
```js

```


## Account API

#### account.isSignedIn()
```js

```

#### account.signUp( { username, password } )
```js

```

#### signIn({username, password})
```js

```

#### signOut()
```js

```

#### changePassword( username, newPassword )
```js

```

#### destroy(username)
```js

```

#### changeUsername( {curUsername, password, newUsername} )
```js

```

## Cushion Worker API

#### cushionWorker.addPushEvent(eventID, eventCallback)
```js

```

#### cushionWorker.addMessageEvent(eventID, eventCallback)
```js

```

#### cushionWorker.addSyncEvent(eventID, eventCallback)
```js

```

#### cushoinWorker.removePushEvent(eventID)
```js

```
