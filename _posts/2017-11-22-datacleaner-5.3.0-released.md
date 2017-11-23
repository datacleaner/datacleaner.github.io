---
layout: post
title: "DataCleaner 5.3.0 released"
subtitle: "A community and contributor focused release"
date: 2017-11-22 21:20:00 -0700
categories: release
---

Over the last couple of months, DataCleaner community members have been working to shape together a new release of DataCleaner that will shape the application and it's source code in a way that is more sustainable from a community and contributor perspective. Today, this release is available. Go to the [Downloads page](/downloads) to get DataCleaner 5.3.0!

Or read on to learn about what's new ...

### Sanitized the source for contributor friendliness

As the community edition and commercial edition of DataCleaner are now effectively separated, <a href="https://github.com/datacleaner/DataCleaner/issues/1753">we decided</a> to go ahead and cut some of the ties and <b>remove complexity</b> that is needed for the enterprise and highly customizable scenarios that DataCleaner have had to cater to, but no longer applies to. Specifically, a number of features aren't available in DataCleaner community edition, which allowed us to trim the codebase considerably:

* The on-demand services from DataCloud are no longer included.
* The integration with DataCleaner monitor is no longer included.
* The ExtensionSwap and RegexSwap content providers are no longer included.
* Deprecated code and backwards compatibility mode for versions prior to DataCleaner 5.0 has been dropped.

It may not seem exciting to just remove things. But for potential contributors, this is a big deal. We've cut away more than <b>18,000 lines of code</b> from the project! This makes it leaner and easier to work with. And we're very happy to have <i>a less involved development pipeline for the community</i>.

### New feature: Fill pattern analyzer

Do you wonder which fields are filled, and depending on what? Is the "state" field of an address always filled, or does it depend on the country? The <b>Fill pattern</b> analyzer lets you discover these relationships.

<div class="newsScreenshot">
	<img src="/assets/release_5.3.0/screenshot_fill_pattern_analyzer_1.png" alt=""/>
</div>

In the screenshot above you see the distribution of how records are filled in a simple data set. Below you see a more complex scenario, where the filling of fields has a high variety of shapes.

<div class="newsScreenshot">
	<img src="/assets/release_5.3.0/screenshot_fill_pattern_analyzer_2.png" alt=""/>
</div>

This feature has been available as a third party extension for a while. Now it is fully integrated into the community edition distribution.

### New feature: Groovy scripting transformer

Another feature that was added in this release, is the Groovy transformer. The new transformer allows you to use the <a href="http://groovy-lang.org">Groovy programming language</a> in your DataCleaner jobs. The transformation is comparable to the well-known JavaScript transformer, but the Groovy language is arguably both faster and more powerful, although JavaScript is perhaps more widely known. Now DataCleaner users have the benefit of choice as they select the scripting language that best fit their problem.

### Basic support for high DPI screens

It has long been a painful experience to use DataCleaner on high DPI devices. With DataCleaner 5.3.0 we've added basic support for high DPI screens. The support here is "basic" in the sense that there are still areas of improvements, but a big step forward has been taken, and the framework has been built for future enhancements too.
