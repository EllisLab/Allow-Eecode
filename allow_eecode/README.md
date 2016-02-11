# Allow EE Code

Allows ExpressionEngine code to be used in entries. **This add-on should be used with extreme caution, if at all. Ask yourself if you should really be putting tags inside _content_. If you are confident the answer is yes, here you go!**

## Usage

### `{exp:allow_eecode}`

#### Example Usage

```
{exp:allow_eecode}

    field whose ExpressionEngine code you want processed (ex: {body})

{/exp:allow_eecode}
```

#### Parameters

- `query` - (y/n) Allow you to allow the use of the {exp:query} tag in your entries. Set to 'n' by default.
- `embed` - (y/n) Allow you to allow the use of {embed} tags in your entries. Set to 'n' by default.

## Change Log

### 2.0

- Updated plugin to be 3.0 compatible

### 1.4

- Updated plugin to be 2.0 compatible

### 1.3

- Updated plugin to work with 1.6.5's typography changes

### 1.2

- Fixed a bug where code containing single variables would not work

### 1.1

- Added embed parameter to tag to enable the use of {embed} tags in entries.

### 1.0.2

- Fixed a bug where any code containing variables pairs would not work (ex: {items} blah {/items})

### 1.0.1

- Removed the ability to use the {exp:query} plugin by default for security reasons.
- Added query parameter to tag to enable the use of {exp:query} in entries.