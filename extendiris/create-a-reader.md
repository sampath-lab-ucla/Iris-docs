---
title: Create A Custom Reader
description: 
  Iris allows for custom data parsers to be added to the system without altering
  source code.
---

## Introduction
When a data file is loaded into Iris, the data handler will check the file type
selected in the file selection window against a list of available readers,
built-in (such as Symphony `*.h5` files) and user defined (See
[Preferences](basicusage/preferences.md):Workspace), in order to determine the
desired data parser function. User-defined parsers can be placed in the
`Readers` folder, located in the user Iris directory