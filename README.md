Phing ESLint
============

## Overview

A collection of ESLint targets for Phing.

## Installation

This project can be checked out with Composer.

Please note that this project assumes that ESLint is installed and configured
and ${eslint.bin} points to its binaries location.

```
"require": {
    "jorgegc/phing-eslint": "*"
}
```

If you are already running a Phing build in an existing project why not
include these tasks as well with the following line in your build.xml:

```
<import file="vendor/jorgegc/phing-eslint/build.xml" optional="true" />
```

## Usage

To get a list of tasks.

```
phing -l
```
