---
layout: post
title: "DataCleaner 5.4.0 released"
subtitle: "Keeping up to date with the quality of your data"
date: 2018-01-22 18:20:00 -0700
categories: release
---

We're happy to announce the availability of DataCleaner Community Edition version 5.4.0! You can grab it on the [Downloads page](/downloads) now. Let's jump right into what's new:

## New analyzer: "Mark rows as..."

We've added the analyzer "Mark rows as ..." to DataCleaner. This is a component that allows you to consume data, present a preview of it, and count records passed to it. A very basic component that lends itself to advanced use cases such as complex filtering, error handling and rule/metric monitoring.

More information in the [Component Library](/docs/5.4.0/components/mark_rows.html).

## Software update notifications

Going forward, DataCleaner will notify you (in the lower right corner of the status bar) of new versions available.

## Minor bugfixes

We've addressed a series of minor bugs that applied to the previous versions:

 * Fix for datacleaner.sh to take arguments #1755
 * Fix ConcurrentModificationException when closing job #1777
 * MetaModel 5.0.1 update #1780
 * High DPI graphical tweaks #1770