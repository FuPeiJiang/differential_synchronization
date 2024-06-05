Differential Synchronization, talk by Neil Fraser: https://www.youtube.com/watch?v=S2Hp_1jqpY8<br>
diff-match-patch: https://github.com/google/diff-match-patch<br>

___

this is a single \<textarea\> which keeps its cursor/caret position after patch
<br>
network sync is every 1000ms<br>
diff sync is every 333ms<br>
<br>
optionally uncomment this line:<br>
```js
if (Math.random() > 0.8) { //simulate packet drop, needs at least 2 clients
```

## Run using:
`bun server.mjs`