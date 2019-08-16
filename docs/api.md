# API 

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
store.delete(documentID).then(id => {
  //
});

```

#### store.destroy()
```js
store.destroy().then( res => {
 // 
});

```

#### store.deleteAll()
```js
store.deleteAll().then(res => {
  // 
});

```


## Account API

#### account.signUp()
```js
account.signUp({username, password}).then( res => {
  //
});
```
#### signIn({username, password})
```js
account.signIn({ 'John', 'secret' }).then( res => {
  //
});

```

#### signOut()
```js
account.signOut().then( res => {
  //
});

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
