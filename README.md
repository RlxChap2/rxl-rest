# rxl-rest

> install npm package: `npm install rxl-rest`

---

## String Code

**This is a simple code for using the string code :**

```js
const rxl = require("rxl-rest");

console.log(rxl("rxl"));
```

- **if the string = rxl**

```console
$ true
```

- **if the string dosen't same the rxl**

```console
$ false
```

## Discord Package Section

> **You can user reply and interaction messages with `rxl-rest` package**

```js
const { reply } = require("rxl-rest");

reply({ message: `Test Message`, interaction: interaction });
```

**Console:**

```console
$ Test Message, UserID: userId, Username: username
```
