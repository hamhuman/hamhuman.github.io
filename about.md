---
layout: page
title: About
permalink: /about/
---

``` javascript
class Page {
  constructor() {
    this.compiledTime = "{{ site.time }}";
    this.getCompiledTime = function() {
      return this.compiledTime;
    }
  }
}

console.log(new Page().getCompileTime());
```
