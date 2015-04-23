Common Form
-----------

[![NPM version](https://img.shields.io/npm/v/commonform.svg)](https://www.npmjs.com/package/commonform)

A dummy package for use as an npm peer dependency:

```json
{
  "peerDependencies": {
	"commonform": "1.x"
  }
}
```

All packages that peer-depend on this package expect as arguments (or return as outputs) form objects that meet the validation criteria of the latest version of [commonform-validate](https://npmjs.com/package/commonform-validate) with the same peer dependency.
