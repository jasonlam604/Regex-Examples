# Regex-Examples

* [Overview](#overview)
* [Patterns](#patterns)
      * [Phone Number North America](#phone-number-north-america)
      * [Postal Code Canadian](#postal-code-canadian)
      
* [Reference Table](#reference-table)


## Overview
Simply a collection of Regex Patterns

## Patterns

#### Phone Number North America

```bash
^\(?([0-9]{3})\)?[-. ]?([0-9]{3})[-. ]?([0-9]{4})$
```

Valid Inputs:

* 555-555-5555
* 555 555-5555
* 555-555 5555
* (555)-555-5555
* (555) 555-5555
* 555 555 5555

#### Postal Code Canadian

```bash
^[A-Za-z]\d[A-Za-z][ -]?\d[A-Za-z]\d$
```

## Reference Table

//Todo

