# styletags_filter
Drupal module to convert embedded CSS styles into tags.

[![CircleCI](https://circleci.com/gh/alexdesignworks/styletags_filter.svg?style=shield)](https://circleci.com/gh/alexdesignworks/styletags_filter)


A list of tag-to-styles mappings. One mapping per line. Tag divided by pipe (|) from style rules.

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
