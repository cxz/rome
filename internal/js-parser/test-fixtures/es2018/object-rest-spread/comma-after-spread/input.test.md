# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2018 > object-rest-spread > comma-after-spread`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2018/object-rest-spread/comma-after-spread/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2018/object-rest-spread/comma-after-spread/input.js"
		end: Object {
			column: 10
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2018/object-rest-spread/comma-after-spread/input.js"
				end: Object {
					column: 10
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSObjectExpression {
				loc: Object {
					filename: "es2018/object-rest-spread/comma-after-spread/input.js"
					end: Object {
						column: 8
						line: 1
					}
					start: Object {
						column: 1
						line: 1
					}
				}
				properties: Array [
					JSSpreadProperty {
						loc: Object {
							filename: "es2018/object-rest-spread/comma-after-spread/input.js"
							end: Object {
								column: 6
								line: 1
							}
							start: Object {
								column: 2
								line: 1
							}
						}
						argument: JSReferenceIdentifier {
							name: "a"
							loc: Object {
								filename: "es2018/object-rest-spread/comma-after-spread/input.js"
								identifierName: "a"
								end: Object {
									column: 6
									line: 1
								}
								start: Object {
									column: 5
									line: 1
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
