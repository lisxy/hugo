---
title: Month
description: Returns the month of the year of the given time.Time value.
categories: []
keywords: []
params:
  functions_and_methods:
    returnType: time.Month
    signatures: [TIME.Month]
---

To convert the `time.Month` value to a string:

```go-html-template
{{ $t := time.AsTime "2023-01-27T23:44:58-08:00" }}
{{ $t.Month.String }} → January
```

To convert the `time.Month` value to an integer.

```go-html-template
{{ $t := time.AsTime "2023-01-27T23:44:58-08:00" }}
{{ $t.Month | int }} → 1
```
