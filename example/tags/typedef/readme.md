# Input source code
```js
/**
A number, or a string containing a number.
@typedef {(number|string)} NumberLike
*/

/**
Set the magic number.
@param {NumberLike} x - The magic number.
*/
function setMagicNumber (x) {}

/**
Some options
@typedef {object} someOptions
@property {boolean} a flag
@property {string} some text
*/

/**
@param {someOptions} - the input options
*/
function doSomething (option) {}

```

* * * 

# jsdoc-parse output
```json
[
  {
    "id": "setMagicNumber",
    "longname": "setMagicNumber",
    "name": "setMagicNumber",
    "scope": "global",
    "kind": "function",
    "description": "Set the magic number.",
    "params": [
      {
        "type": {
          "names": [
            "NumberLike"
          ]
        },
        "description": "The magic number.",
        "name": "x"
      }
    ],
    "meta": {
      "lineno": 10,
      "filename": "src.js",
      "path": "/Users/lloyd/Documents/75lb/jsdoc-to-markdown/example/tags/typedef"
    },
    "order": 1
  },
  {
    "id": "doSomething",
    "longname": "doSomething",
    "name": "doSomething",
    "scope": "global",
    "kind": "function",
    "params": [
      {
        "type": {
          "names": [
            "someOptions"
          ]
        },
        "description": "the input options",
        "name": "option"
      }
    ],
    "meta": {
      "lineno": 22,
      "filename": "src.js",
      "path": "/Users/lloyd/Documents/75lb/jsdoc-to-markdown/example/tags/typedef"
    },
    "order": 3
  },
  {
    "id": "NumberLike",
    "longname": "NumberLike",
    "name": "NumberLike",
    "scope": "global",
    "kind": "typedef",
    "description": "A number, or a string containing a number.",
    "type": {
      "names": [
        "number",
        "string"
      ]
    },
    "meta": {
      "lineno": 1,
      "filename": "src.js",
      "path": "/Users/lloyd/Documents/75lb/jsdoc-to-markdown/example/tags/typedef"
    },
    "order": 0
  },
  {
    "id": "someOptions",
    "longname": "someOptions",
    "name": "someOptions",
    "scope": "global",
    "kind": "typedef",
    "description": "Some options",
    "type": {
      "names": [
        "object"
      ]
    },
    "properties": [
      {
        "type": {
          "names": [
            "boolean"
          ]
        },
        "description": "flag",
        "name": "a"
      },
      {
        "type": {
          "names": [
            "string"
          ]
        },
        "description": "text",
        "name": "some"
      }
    ],
    "meta": {
      "lineno": 12,
      "filename": "src.js",
      "path": "/Users/lloyd/Documents/75lb/jsdoc-to-markdown/example/tags/typedef"
    },
    "order": 2
  }
]
```

* * * 

# dmd output
```markdown
<a name="setMagicNumber"></a>
#### setMagicNumber(x)
Set the magic number.

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| x | <code>[NumberLike](#NumberLike)</code> | The magic number. |

<a name="doSomething"></a>
#### doSomething(option)
**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| option | <code>[someOptions](#someOptions)</code> | the input options |

<a name="NumberLike"></a>
#### NumberLike : <code>number</code> &#124; <code>string</code>
A number, or a string containing a number.

**Kind**: global typedef  
<a name="someOptions"></a>
#### someOptions : <code>object</code>
Some options

**Kind**: global typedef  
**Properties**

| Name | Type | Description |
| --- | --- | --- |
| a | <code>boolean</code> | flag |
| some | <code>string</code> | text |

```

* * * 

# Rendered
<a name="setMagicNumber"></a>
#### setMagicNumber(x)
Set the magic number.

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| x | <code>[NumberLike](#NumberLike)</code> | The magic number. |

<a name="doSomething"></a>
#### doSomething(option)
**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| option | <code>[someOptions](#someOptions)</code> | the input options |

<a name="NumberLike"></a>
#### NumberLike : <code>number</code> &#124; <code>string</code>
A number, or a string containing a number.

**Kind**: global typedef  
<a name="someOptions"></a>
#### someOptions : <code>object</code>
Some options

**Kind**: global typedef  
**Properties**

| Name | Type | Description |
| --- | --- | --- |
| a | <code>boolean</code> | flag |
| some | <code>string</code> | text |

