# `noSetterReturn.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-compiler/transforms/lint/noSetterReturn.test.ts --update-snapshots` to update.

## `format disabled in project config should not regenerate the file`

```
✔ No known problems!

```

## `format enabled in project config should result in regenerated file`

### `0`

```
✔ No known problems!

```

### `0: formatted`

```
foobar('yes');

```

## `no setter return`

### `0`

```

 unknown:5:10 lint/noSetterReturn ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Setter cannot return a value

    3 │       set name(value) {
    4 │         if (!value) {
  > 5 │           return 'wrong';
      │           ^^^^^^^^^^^^^^^ 
    6 │         }
    7 │       }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1`

```

 unknown:5:10 lint/noSetterReturn ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Setter cannot return a value

    3 │       static set name(value) {
    4 │         if (!value) {
  > 5 │           return 'wrong';
      │           ^^^^^^^^^^^^^^^ 
    6 │         }
    7 │       }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `2`

```

 unknown:5:10 lint/noSetterReturn ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Setter cannot return a value

    3 │       set name(value) {
    4 │         if (!value) {
  > 5 │           return 'wrong';
      │           ^^^^^^^^^^^^^^^ 
    6 │         }
    7 │       }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `3`

```
✔ No known problems!

```
