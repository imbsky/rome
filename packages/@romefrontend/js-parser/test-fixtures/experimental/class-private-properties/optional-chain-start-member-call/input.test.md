# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-private-properties > optional-chain-start-member-call`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 85
			line: 8
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Expected an identifier"}
			}
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 16
					index: 64
					line: 5
				}
				start: Object {
					column: 16
					index: 64
					line: 5
				}
			}
		}
	]
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: Object {
					filename: "input.js"
					identifierName: "Foo"
					end: Object {
						column: 9
						index: 9
						line: 1
					}
					start: Object {
						column: 6
						index: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 1
					index: 84
					line: 7
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 1
						index: 84
						line: 7
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: Array [
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "input.js"
									identifierName: "x"
									end: Object {
										column: 11
										index: 23
										line: 2
									}
									start: Object {
										column: 10
										index: 22
										line: 2
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 11
									index: 23
									line: 2
								}
								start: Object {
									column: 9
									index: 21
									line: 2
								}
							}
						}
						value: JSNumericLiteral {
							value: 1
							format: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 15
									index: 27
									line: 2
								}
								start: Object {
									column: 14
									index: 26
									line: 2
								}
							}
						}
						typeAnnotation: undefined
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 16
								index: 28
								line: 2
							}
							start: Object {
								column: 2
								index: 14
								line: 2
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								index: 14
								line: 2
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 11
									index: 23
									line: 2
								}
								start: Object {
									column: 2
									index: 14
									line: 2
								}
							}
						}
					}
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: Object {
									filename: "input.js"
									identifierName: "test"
									end: Object {
										column: 13
										index: 43
										line: 4
									}
									start: Object {
										column: 9
										index: 39
										line: 4
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 13
									index: 43
									line: 4
								}
								start: Object {
									column: 9
									index: 39
									line: 4
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 3
								index: 82
								line: 6
							}
							start: Object {
								column: 2
								index: 32
								line: 4
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 15
									index: 45
									line: 4
								}
								start: Object {
									column: 13
									index: 43
									line: 4
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								index: 32
								line: 4
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 13
									index: 43
									line: 4
								}
								start: Object {
									column: 2
									index: 32
									line: 4
								}
							}
						}
						body: JSBlockStatement {
							directives: Array []
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 3
									index: 82
									line: 6
								}
								start: Object {
									column: 16
									index: 46
									line: 4
								}
							}
							body: Array [
								JSReturnStatement {
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 17
											index: 65
											line: 5
										}
										start: Object {
											column: 4
											index: 52
											line: 5
										}
									}
									argument: JSMemberExpression {
										loc: Object {
											filename: "input.js"
											end: Object {
												column: 17
												index: 65
												line: 5
											}
											start: Object {
												column: 11
												index: 59
												line: 5
											}
										}
										object: JSReferenceIdentifier {
											name: "Foo"
											loc: Object {
												filename: "input.js"
												identifierName: "Foo"
												end: Object {
													column: 14
													index: 62
													line: 5
												}
												start: Object {
													column: 11
													index: 59
													line: 5
												}
											}
										}
										property: JSStaticMemberProperty {
											value: JSIdentifier {
												name: ""
												loc: Object {
													filename: "input.js"
													identifierName: ""
													end: Object {
														column: 17
														index: 65
														line: 5
													}
													start: Object {
														column: 16
														index: 64
														line: 5
													}
												}
											}
											optional: true
											loc: Object {
												filename: "input.js"
												identifierName: ""
												end: Object {
													column: 17
													index: 65
													line: 5
												}
												start: Object {
													column: 16
													index: 64
													line: 5
												}
											}
										}
									}
								}
								JSExpressionStatement {
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 30
											index: 78
											line: 5
										}
										start: Object {
											column: 17
											index: 65
											line: 5
										}
									}
									expression: JSCallExpression {
										loc: Object {
											filename: "input.js"
											end: Object {
												column: 29
												index: 77
												line: 5
											}
											start: Object {
												column: 17
												index: 65
												line: 5
											}
										}
										arguments: Array [
											JSNumericLiteral {
												value: 2
												format: undefined
												loc: Object {
													filename: "input.js"
													end: Object {
														column: 28
														index: 76
														line: 5
													}
													start: Object {
														column: 27
														index: 75
														line: 5
													}
												}
											}
										]
										callee: JSMemberExpression {
											loc: Object {
												filename: "input.js"
												end: Object {
													column: 26
													index: 74
													line: 5
												}
												start: Object {
													column: 17
													index: 65
													line: 5
												}
											}
											object: JSReferenceIdentifier {
												name: "x"
												loc: Object {
													filename: "input.js"
													identifierName: "x"
													end: Object {
														column: 18
														index: 66
														line: 5
													}
													start: Object {
														column: 17
														index: 65
														line: 5
													}
												}
											}
											property: JSStaticMemberProperty {
												value: JSIdentifier {
													name: "toFixed"
													loc: Object {
														filename: "input.js"
														identifierName: "toFixed"
														end: Object {
															column: 26
															index: 74
															line: 5
														}
														start: Object {
															column: 19
															index: 67
															line: 5
														}
													}
												}
												loc: Object {
													filename: "input.js"
													identifierName: "toFixed"
													end: Object {
														column: 26
														index: 74
														line: 5
													}
													start: Object {
														column: 19
														index: 67
														line: 5
													}
												}
											}
										}
									}
								}
							]
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

 input.js:5:16 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected an identifier

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
