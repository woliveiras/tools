# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-array-binding-pattern > array-binding-pattern-03`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
		end: Object {
			column: 0
			index: 15
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
				end: Object {
					column: 14
					index: 14
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSArrowFunctionExpression {
				loc: Object {
					filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
					end: Object {
						column: 13
						index: 13
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
						end: Object {
							column: 13
							index: 13
							line: 1
						}
						start: Object {
							column: 12
							index: 12
							line: 1
						}
					}
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					rest: undefined
					returnType: undefined
					thisType: undefined
					loc: Object {
						filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
						end: Object {
							column: 12
							index: 12
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
					params: Array [
						JSBindingArrayPattern {
							loc: Object {
								filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
								end: Object {
									column: 9
									index: 9
									line: 1
								}
								start: Object {
									column: 1
									index: 1
									line: 1
								}
							}
							rest: JSBindingIdentifier {
								name: "b"
								loc: Object {
									filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
									identifierName: "b"
									end: Object {
										column: 8
										index: 8
										line: 1
									}
									start: Object {
										column: 7
										index: 7
										line: 1
									}
								}
							}
							elements: Array [
								JSBindingIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-array-binding-pattern/array-binding-pattern-03/input.js"
										identifierName: "a"
										end: Object {
											column: 3
											index: 3
											line: 1
										}
										start: Object {
											column: 2
											index: 2
											line: 1
										}
									}
								}
							]
						}
					]
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