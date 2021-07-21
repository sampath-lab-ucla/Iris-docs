---
title: Iris Data Core
description: The layout of the Iris data handler.
---

```dos
src
├───+iris
│   ├───...
│   ├───+data
│   │   ├───Datum.m
│   │   └───Handler.m
│   └───...
└───@Iris
```

## Introduction
Iris loads data into an array of the `iris.data.Datum` class and manages access
to the data through the `iris.data.Handler` class. The 