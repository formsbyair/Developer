---
title: Aggregate Functions
category: Questions
order: 1
---

The following functions can be used in formula expressions to aggregate data across repeated questions with the same tag.

|Function|Definition|Example|
|---|---|---|
|any(&lt;&lt;tag&gt;&gt;)|Boolean indicating if there is any occurence of a question with *tag* DEPRECATED: USE [Any]({{ site.baseurl }}/tags/functions/any)|true|
|average(&lt;&lt;tag&gt;&gt;)|The numeric average of question values with *tag*|10|
|join(&lt;&lt;tag&gt;&gt;)|A comma separated string of all question values with *tag* DEPRECATED: USE [ForEach]({{ site.baseurl }}/tags/functions/foreach)|1,2,3|
|sum(&lt;&lt;tag&gt;&gt;)|The numeric sum of question values with *tag*|100|
|unique(&lt;&lt;tag&gt;&gt;)|Boolean indicating if all question values with *tag* are unique|false|

## Sample Expressions

sum(&lt;&lt;Amount&gt;&gt;)

&apos;join(&lt;&lt;Option&gt;&gt;)&apos;

any(&lt;&lt;Warning&gt;&gt;) ? &apos;You have warnings&apos; : &apos;&apos;