---
layout: post
title: "DataCleaner 5.7.0 released"
subtitle: "Machine Learning components, support for DynamoDB, more."
date: 2019-04-01 12:22:00 -0700
categories: release
---

No, this is not an April's fool's post. We're releasing DataCleaner 5.7.0 today and it's pretty cool stuff coming out!

Grab it here -- [Downloads](/downloads) -- or keep reading for more information.

## Machine Learning

DataCleaner 5.7.0 includes half a dusin new components all resolving around the topic of Machine Learning. As the data quality engineer's toolkit, we found it naturally to also expand DataCleaner's applicability into the realm of ML. With DataCleaner 5.7.0 you can thus train and apply ML models on every data source that DataCleaner supports. 

<div class="newsScreenshot">
	<img src="/assets/release_5.7.0/ml.png" alt=""/>
</div>

Grab the software or check out the [Documentation](/documentation) for details about the new components.

## Amazon AWS DynamoDB

We've added support for Amazon AWS DynamoDB. So for those cloud database users out there, you've no longer got an excuse not to use DataCleaner.

<div class="newsScreenshot">
	<img src="/assets/release_5.7.0/db.png" style="width: 40%" alt=""/>
</div>

## More stuff

We've added a new _String contains filter_ component which lets you easily filter out records that contains particular text snippets.

A bug was fixed in the Pattern Finder analyzer, which caused it's initial configuration for parsing/identifying numbers to be locale-dependent.
