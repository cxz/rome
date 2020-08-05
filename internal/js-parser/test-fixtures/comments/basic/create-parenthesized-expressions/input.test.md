# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `comments > basic > create-parenthesized-expressions`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "comments/basic/create-parenthesized-expressions/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "comments/basic/create-parenthesized-expressions/input.js"
		end: Object {
			column: 0
			line: 13
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: " One"
			loc: Object {
				filename: "comments/basic/create-parenthesized-expressions/input.js"
				end: Object {
					column: 6
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
		}
		CommentBlock {
			id: "1"
			value: " Two "
			loc: Object {
				filename: "comments/basic/create-parenthesized-expressions/input.js"
				end: Object {
					column: 9
					line: 4
				}
				start: Object {
					column: 0
					line: 4
				}
			}
		}
		CommentLine {
			id: "2"
			value: " Three"
			loc: Object {
				filename: "comments/basic/create-parenthesized-expressions/input.js"
				end: Object {
					column: 10
					line: 8
				}
				start: Object {
					column: 2
					line: 8
				}
			}
		}
		CommentBlock {
			id: "3"
			value: " Four "
			loc: Object {
				filename: "comments/basic/create-parenthesized-expressions/input.js"
				end: Object {
					column: 11
					line: 12
				}
				start: Object {
					column: 1
					line: 12
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			leadingComments: Array ["0"]
			trailingComments: Array ["1"]
			loc: Object {
				filename: "comments/basic/create-parenthesized-expressions/input.js"
				end: Object {
					column: 4
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			expression: JSNumericLiteral {
				value: 1
				format: undefined
				leadingComments: undefined
				loc: Object {
					filename: "comments/basic/create-parenthesized-expressions/input.js"
					end: Object {
						column: 2
						line: 2
					}
					start: Object {
						column: 1
						line: 2
					}
				}
			}
		}
		JSExpressionStatement {
			leadingComments: Array ["1"]
			loc: Object {
				filename: "comments/basic/create-parenthesized-expressions/input.js"
				end: Object {
					column: 4
					line: 5
				}
				start: Object {
					column: 0
					line: 5
				}
			}
			expression: JSNumericLiteral {
				value: 2
				format: undefined
				leadingComments: undefined
				loc: Object {
					filename: "comments/basic/create-parenthesized-expressions/input.js"
					end: Object {
						column: 2
						line: 5
					}
					start: Object {
						column: 1
						line: 5
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "comments/basic/create-parenthesized-expressions/input.js"
				end: Object {
					column: 2
					line: 10
				}
				start: Object {
					column: 0
					line: 7
				}
			}
			expression: JSNumericLiteral {
				value: 3
				format: undefined
				leadingComments: Array ["2"]
				loc: Object {
					filename: "comments/basic/create-parenthesized-expressions/input.js"
					end: Object {
						column: 3
						line: 9
					}
					start: Object {
						column: 2
						line: 9
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "comments/basic/create-parenthesized-expressions/input.js"
				end: Object {
					column: 15
					line: 12
				}
				start: Object {
					column: 0
					line: 12
				}
			}
			expression: JSNumericLiteral {
				value: 4
				format: undefined
				leadingComments: Array ["3"]
				loc: Object {
					filename: "comments/basic/create-parenthesized-expressions/input.js"
					end: Object {
						column: 13
						line: 12
					}
					start: Object {
						column: 12
						line: 12
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```