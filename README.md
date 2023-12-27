# react-state-implementation

Implement updateState feature of react using vanilla javascript and DOM manipulation

1. clone the repo and open [index.html](index.html) in a browser.
2. open console under chrome dev tools using inspect element.
3. run the below commands one by one.

```js
initialState = JSON.parse(
    '[{"title":"First Todo","description":"Hey there","id":1},{"title":"Second Todo","description":"I will be removed soon","id":2},{"title":"Third Todo","description":"I will be updated soon","id":3}]'
);
```

```js
updateState(initialState);
```

```js
newState = JSON.parse(
    '[{"title":"First Todo","description":"Hey there","id":1},{"title":"Third Todo updated","description":"I am be updated now","id":3}]'
);
```

```js
updateState(newState);
```
