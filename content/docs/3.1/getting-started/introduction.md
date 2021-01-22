---
layout: docs
title: Introduction
description: Data Entry is one of part of Auto Clicker extension and its not separate extension all together
group: getting-started
aliases:
  - "/docs/3.1/getting-started/"
  - "/docs/getting-started/"
  - "/getting-started/"
toc: true
---

## Quick start

* [Download extension.]({{<docsref "/getting-started/download">}})
* Open data entry sheet 
  * https://dev.getdataentry.com
* Enter Sheet name
* Fill data into sheet / Import CSV file which auto imports into sheet (recommended)
* Columns are ref using letter `A`-`Z`
* Rows are ref from `0`-`50`
* To use particular field in AutoClicker inside Value field use below syntax
* Sheet::`sheet-name`::`A1` - this will point to sheet with name as `sheet-name` and `first` column and `first` row
* Sheet::`sheet-name`::`A2` - this will point to sheet with name as `sheet-name` and `first` column and `second` row
* Sheet::`sheet-name`::`B1` - this will point to sheet with name as `sheet-name` and `second` column and `first` row
* Sheet::`sheet-name`::`B2` - this will point to sheet with name as `sheet-name` and `second` column and `second` row
* Sheet::`sheet-name`::`A$` - this will point to sheet with name as `sheet-name` and `first` column and rows will iterate with batch repeat

## More Options

{{<param name>}}l extension consist of 2 major parts 
- [Sheet-list]({{<docsref "/sheet-list/overview">}}) - it consist of all configuration
- [Sheet]({{<docsref "/sheet/overview">}}) - combination of url and actions

## Community

Stay up to date on the features of {{<param name>}} and reach out to the community with these helpful resources.

- Follow [@dhruvtechapps on Twitter](https://twitter.com/{{< param twitter >}}).
- Read and subscribe to [The Official AutoClicker Blog]({{< param blog >}}).
- Join [the official Discord server]({{< param discord >}}).

[//]: # (You can also follow [@getdataentry on Twitter](https://twitter.com/{{< param twitter >}}) for the latest gossip and awesome music videos.)
