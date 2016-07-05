# styletags_filter
Drupal module to convert embedded CSS styles into tags.

[![CircleCI](https://circleci.com/gh/alexdesignworks/styletags_filter.svg?style=shield)](https://circleci.com/gh/alexdesignworks/styletags_filter)

Converts this
```
<style>
  .myclass {
    font-weight: bold;
  }
</style>
  
<span class="myclass">
  some bold text
</span>
```
to this
```
<strong>
  some bold text
</strong>
```
## Use-case
1. Content is already imported from 3-rd party resource, but embedded styles override theme styles.
 
2. Content being imported from 3-rd party and this filter can be used to cleanup embedded styles.
