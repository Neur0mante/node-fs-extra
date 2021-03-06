# writeJson(file, object, [options], callback)

Writes an object to a JSON file. `options` are the same that
you'd pass to [`jsonFile.writeFile()`](https://github.com/jprichardson/node-jsonfile#writefilefilename-options-callback).

**Alias:** `writeJSON()`

**Sync:** `writeJsonSync()`, `writeJSONSync()`

## Example:

```js
const fs = require('fs-extra')

fs.writeJson('./package.json', {name: 'fs-extra'}, err => {
  if (err) return console.error(err)

  console.log('success!')
})
```

---

**See also:** [`outputJson()`](outputJson.md)
