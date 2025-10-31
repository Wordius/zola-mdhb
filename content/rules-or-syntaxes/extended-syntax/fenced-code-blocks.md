+++
title = "Fenced code blocks in markdown"
description = "Having the ability to fence off code blocks is useful when you are trying to explain a programming language. You can also add a splash of colour to your syntax"
weight = 200
+++

By default, markdown creates code blocks when lines are indented by four spaces or one tab. Fenced code blocks offer an easier alternative, with no indentation required.

Use three backticks or three tildes to start and end a fenced code block:

````
```
{
"firstName": "John",
"lastName": "Smith",
"age": 30
}
```
````

Renders as this:

```
{
"firstName": "John",
"lastName": "Smith",
"age": 30
}
```

## Syntax highlighting

Many markdown processors support syntax highlighting for fenced code blocks. This feature adds colour and formatting based on the language specified. You specify the language directly after the opening backticks:

````
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
````

Which renders like this:

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 30
}
```