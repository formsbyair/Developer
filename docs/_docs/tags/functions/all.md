---
title: Functions > All
category: Tags
order: 1
---

Returns true if all Repeater items satisfy a Condition, otherwise false

## Syntax

&lt;&lt;[**All**:Repeater{Condition}]&gt;&gt; <span class="badge platform">Server</span>

#### Repeater <span class="badge platform">Required</span>
Tag name of repeater

#### Condition <span class="badge platform">Required</span>
Boolean expression to match repeater items e.g. {&apos;&lt;&lt;Type&gt;&gt;&apos; == &apos;Primary&apos;}

## Examples

|Function|Result|
|---|---|
|&lt;&lt;[All:Contact{&apos;&lt;&lt;Type&gt;&gt;&apos; == &apos;Primary&apos;}]&gt;&gt;|false|