# \<oe-validators\>

>## This project is no longer maintained. Form validators are now part of [oe-ui-forms](https://github.com/EdgeVerve/oe-ui-forms)

`<oe-validators>` provides a collection of elements for validation of forms.

This repo consists of the following validator elements

* oe-async-validator
* oe-block-validator
* oe-combination-validator
* oe-eq-validator
* oe-expression-validator
* oe-le-validator
* oe-lt-validator
* oe-ne-validator

### oe-block-validator
`oe-block-validator` provides a validation section to validate a subset of fields on form.

```html
<oe-block-validator>
    <oe-vbox>
        <paper-input label="First Name"></paper-input>
        <paper-input label="Last Name"></paper-input>
        <paper-input label="City"></paper-input>
        <paper-input label="Zip Code"></paper-input>
    </oe-vbox>
<oe-block-validator>
```

### oe-combination-validator
`oe-combination-validator` evaluates fields on the bound `model` and ensures the combination is one of the defined `combinations`.

### oe-eq-validator
`oe-eq-validator` evaluates values of two fields on the bound `model` to make sure they are equal/same.

### oe-expression-validator
`oe-expression-validator` evaluates an `expression` on the bound `model` to decide the model validity.

### oe-le-validator
`oe-le-validator` evaluates values of two fields on the bound `model` to make sure value of first field (fields[0]) is less-than-or-equal-to the second field (fields[1]).

### oe-lt-validator
`oe-lt-validator` evaluates values of two fields on the bound `model` to make sure value of first field (fields[0]) is less-than second field (fields[1]).

### oe-ne-validator
`oe-ne-validator` evaluates values of two fields on the bound `model` to make sure they are *not* same.

