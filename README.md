##How to use##
Add script and then edit your CSS )

You can create CSS rules now:
```
.[OS].[Browser] css selector
```

OS selectors:
```
.win — Windows
.linux — Linux
.mac — MacOS`
```

Browser selectors:
```
`.ie — all IE versions
.ie8 — IE 8.х
.ie7 — IE 7.x
.ie6 — IE 6.x
.ie5 — IE 5.x
.gecko — all firefox versiona and other gecko browsers
.ff2 — firefox 2
.ff3 — firefox 3
.opera — all opera versions
.opera8 — opera 8.x
.opera9 — opera 9.x
.konqueror — konqueror
.safari — safari`
```

Example:
```
.mac.gecko selector{/* fixed code */}
.mac.ff2(3) selector{/* fixed code */}
```

Look at priorities:
```
`.win.ff3 #id{background: #aaa} /* 1 */
.win.gecko #id{background: #f00} /* 2 */
.ff3 #id{background:#333} /* 3 */
.gecko #id{background:#00f} /* 4 */
.win #id{background: #ff0} /* 5 */`
```
