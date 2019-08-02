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

console.log(new Page().getCompiledTime());
```

### History

``` shell
* c857262 (HEAD -> master, origin/master, origin/HEAD) correction markdown
* ebe4825 mod about
* bf823ff sync with herdin.github.io write post - hamhuman 03
* 1577638 repositioning
* dc43d84 add github
*   1a10262 Merge branch 'master' of https://github.com/herdin/hamhuman.github.io
|\
| *   2f0eb5a Merge branch 'master' into master
| |\
| | * 841d13b Set theme jekyll-theme-minimal
| | *   5fe6a01 Merge pull request #6 from herdin/master
| | |\
* | | | 2ec3d41 BAMB!!!
|/ / /
* | | 9f2e27f modify theme
| |/
|/|
* | 2c12798 모임전 포스팅
|/
*   197ec44 (hamhuman-origin/master) Merge pull request #5 from herdin/master
|\
| * 540c023 add posts
* |   90bab14 Merge pull request #4 from swampwar/master
|\ \
| * | 5b20b9d first
* | |   86eb65f Merge pull request #3 from herdin/develop
|\ \ \
| * | | 6ecfe88 (origin/develop) herdin pull request
| | |/
| |/|
* | |   fcc7ff7 Merge pull request #2 from shro1005/master
|\ \ \
| * | | 23fbd9b commit
| * | | b738c40 commit
| |/ /
* | |   6da9d44 Merge pull request #1 from redPC/pull-test-red
|\ \ \
| |/ /
|/| |
| * | a037f67 2019-07-12-redPC-test.md edit
|/ /
* | 67c8beb add post
* | 687c361 add post
|/
* a01d293 add post
* 80525ac mod default layout
* 1b95cd4 blog to log
* 3c926af blog to log
* a236c1a mod blog
* 49d3f17 mod post
* 4218621 add post
* aaf8694 mod post index
* 65ab40b code syntax set java
* 566c0da add post code
* 0d40bcc mod titles
* 7b2cb63 add post
* 193c982 add atom
* b0a5554 mod config
* 9608f8f add blog
* 18fdfd0 mod index
* 20fc7d0 mod index
* e9e4aef mod index
* 6e9b708 test
* 4378a37 mod date
* fc06347 add first post
* 35d3417 mod index content
* 39b69da mod layout
* 7375625 mod index
* c1cba68 index, config
* c7a858b 1
* 328f53f add ignore
* 04cf737 add index

```
