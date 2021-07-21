---
title: The Core Structure
description: Iris comprises 2 main elements; the data core and the UI.
---

## Introduction
Iris was written around data, that is, I thought it most pertinent to
build a data management class and then wrap it up with a user interface and
allow the user to do what they wish with their data. I sought to make Iris a
MATLAB based application for ease of shareability, compatibility and
extensibility. I took an object-oriented approach to designing the core
mechanism and leveraged MATLAB's vectorized language in an attempt to simplify
and encapsulate data in as few classes as possible. Over the years, the Iris UI
has changed, moving first from traditional java based figures to the newer
web-based figures, but the core of the application mostly remained the same.

## [Data Core](data-core.md)
The Iris data core is comprised of a Datum class and its Handler.

## [User Interface](user-interface.md)
The Iris user-interface is a collection of *figure* windows each served from a
menu servicing class, which handles thier creation and desctruction from the
main application. The UI is served through the [primary view](../basicusage/README.md) and the
[preferences](../basicusage/preferences.md) window, though the user may find that 
navigating larger datasets is easier through the [Data Overview](../basicusage/navigation.md).