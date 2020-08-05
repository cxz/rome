# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2020 > optional-chaining > parenthised-chain`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2020/optional-chaining/parenthised-chain/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2020/optional-chaining/parenthised-chain/input.js"
		end: Object {
			column: 15
			line: 5
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2020/optional-chaining/parenthised-chain/input.js"
				end: Object {
					column: 9
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSMemberExpression {
				loc: Object {
					filename: "es2020/optional-chaining/parenthised-chain/input.js"
					end: Object {
						column: 8
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				property: JSStaticMemberProperty {
					value: JSIdentifier {
						name: "c"
						loc: Object {
							filename: "es2020/optional-chaining/parenthised-chain/input.js"
							identifierName: "c"
							end: Object {
								column: 8
								line: 1
							}
							start: Object {
								column: 7
								line: 1
							}
						}
					}
					loc: Object {
						filename: "es2020/optional-chaining/parenthised-chain/input.js"
						identifierName: "c"
						end: Object {
							column: 8
							line: 1
						}
						start: Object {
							column: 7
							line: 1
						}
					}
				}
				object: JSMemberExpression {
					loc: Object {
						filename: "es2020/optional-chaining/parenthised-chain/input.js"
						end: Object {
							column: 5
							line: 1
						}
						start: Object {
							column: 1
							line: 1
						}
					}
					object: JSReferenceIdentifier {
						name: "a"
						loc: Object {
							filename: "es2020/optional-chaining/parenthised-chain/input.js"
							identifierName: "a"
							end: Object {
								column: 2
								line: 1
							}
							start: Object {
								column: 1
								line: 1
							}
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "b"
							loc: Object {
								filename: "es2020/optional-chaining/parenthised-chain/input.js"
								identifierName: "b"
								end: Object {
									column: 5
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
						}
						optional: true
						loc: Object {
							filename: "es2020/optional-chaining/parenthised-chain/input.js"
							identifierName: "b"
							end: Object {
								column: 5
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2020/optional-chaining/parenthised-chain/input.js"
				end: Object {
					column: 11
					line: 3
				}
				start: Object {
					column: 0
					line: 3
				}
			}
			expression: JSCallExpression {
				arguments: Array []
				loc: Object {
					filename: "es2020/optional-chaining/parenthised-chain/input.js"
					end: Object {
						column: 10
						line: 3
					}
					start: Object {
						column: 0
						line: 3
					}
				}
				callee: JSMemberExpression {
					loc: Object {
						filename: "es2020/optional-chaining/parenthised-chain/input.js"
						end: Object {
							column: 8
							line: 3
						}
						start: Object {
							column: 0
							line: 3
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "c"
							loc: Object {
								filename: "es2020/optional-chaining/parenthised-chain/input.js"
								identifierName: "c"
								end: Object {
									column: 8
									line: 3
								}
								start: Object {
									column: 7
									line: 3
								}
							}
						}
						loc: Object {
							filename: "es2020/optional-chaining/parenthised-chain/input.js"
							identifierName: "c"
							end: Object {
								column: 8
								line: 3
							}
							start: Object {
								column: 7
								line: 3
							}
						}
					}
					object: JSMemberExpression {
						loc: Object {
							filename: "es2020/optional-chaining/parenthised-chain/input.js"
							end: Object {
								column: 5
								line: 3
							}
							start: Object {
								column: 1
								line: 3
							}
						}
						object: JSReferenceIdentifier {
							name: "a"
							loc: Object {
								filename: "es2020/optional-chaining/parenthised-chain/input.js"
								identifierName: "a"
								end: Object {
									column: 2
									line: 3
								}
								start: Object {
									column: 1
									line: 3
								}
							}
						}
						property: JSStaticMemberProperty {
							value: JSIdentifier {
								name: "b"
								loc: Object {
									filename: "es2020/optional-chaining/parenthised-chain/input.js"
									identifierName: "b"
									end: Object {
										column: 5
										line: 3
									}
									start: Object {
										column: 4
										line: 3
									}
								}
							}
							optional: true
							loc: Object {
								filename: "es2020/optional-chaining/parenthised-chain/input.js"
								identifierName: "b"
								end: Object {
									column: 5
									line: 3
								}
								start: Object {
									column: 4
									line: 3
								}
							}
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2020/optional-chaining/parenthised-chain/input.js"
				end: Object {
					column: 15
					line: 5
				}
				start: Object {
					column: 0
					line: 5
				}
			}
			expression: JSMemberExpression {
				loc: Object {
					filename: "es2020/optional-chaining/parenthised-chain/input.js"
					end: Object {
						column: 14
						line: 5
					}
					start: Object {
						column: 0
						line: 5
					}
				}
				property: JSStaticMemberProperty {
					value: JSIdentifier {
						name: "e"
						loc: Object {
							filename: "es2020/optional-chaining/parenthised-chain/input.js"
							identifierName: "e"
							end: Object {
								column: 14
								line: 5
							}
							start: Object {
								column: 13
								line: 5
							}
						}
					}
					optional: true
					loc: Object {
						filename: "es2020/optional-chaining/parenthised-chain/input.js"
						identifierName: "e"
						end: Object {
							column: 14
							line: 5
						}
						start: Object {
							column: 13
							line: 5
						}
					}
				}
				object: JSMemberExpression {
					loc: Object {
						filename: "es2020/optional-chaining/parenthised-chain/input.js"
						end: Object {
							column: 11
							line: 5
						}
						start: Object {
							column: 0
							line: 5
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "d"
							loc: Object {
								filename: "es2020/optional-chaining/parenthised-chain/input.js"
								identifierName: "d"
								end: Object {
									column: 11
									line: 5
								}
								start: Object {
									column: 10
									line: 5
								}
							}
						}
						loc: Object {
							filename: "es2020/optional-chaining/parenthised-chain/input.js"
							identifierName: "d"
							end: Object {
								column: 11
								line: 5
							}
							start: Object {
								column: 10
								line: 5
							}
						}
					}
					object: JSMemberExpression {
						loc: Object {
							filename: "es2020/optional-chaining/parenthised-chain/input.js"
							end: Object {
								column: 9
								line: 5
							}
							start: Object {
								column: 0
								line: 5
							}
						}
						property: JSStaticMemberProperty {
							value: JSIdentifier {
								name: "c"
								loc: Object {
									filename: "es2020/optional-chaining/parenthised-chain/input.js"
									identifierName: "c"
									end: Object {
										column: 9
										line: 5
									}
									start: Object {
										column: 8
										line: 5
									}
								}
							}
							optional: true
							loc: Object {
								filename: "es2020/optional-chaining/parenthised-chain/input.js"
								identifierName: "c"
								end: Object {
									column: 9
									line: 5
								}
								start: Object {
									column: 8
									line: 5
								}
							}
						}
						object: JSMemberExpression {
							loc: Object {
								filename: "es2020/optional-chaining/parenthised-chain/input.js"
								end: Object {
									column: 5
									line: 5
								}
								start: Object {
									column: 1
									line: 5
								}
							}
							object: JSReferenceIdentifier {
								name: "a"
								loc: Object {
									filename: "es2020/optional-chaining/parenthised-chain/input.js"
									identifierName: "a"
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
							property: JSStaticMemberProperty {
								value: JSIdentifier {
									name: "b"
									loc: Object {
										filename: "es2020/optional-chaining/parenthised-chain/input.js"
										identifierName: "b"
										end: Object {
											column: 5
											line: 5
										}
										start: Object {
											column: 4
											line: 5
										}
									}
								}
								optional: true
								loc: Object {
									filename: "es2020/optional-chaining/parenthised-chain/input.js"
									identifierName: "b"
									end: Object {
										column: 5
										line: 5
									}
									start: Object {
										column: 4
										line: 5
									}
								}
							}
						}
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