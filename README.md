# auto-acf
## Intro
Do you hate configuring ACF? Wish it could be done automatically without leaving the text editor? If so this project is for you.

## Roadmap
  - create a basic parser
    - start with all text fields
    - figure a way to determine field type from comment
    - figure a way to determine field type automatically
  - create an acf json file from parsed data
    - find a way to validate it against existing field groups
    - find a way to autoload it

## Synthax Brainstorming

### @comment
```php
<?php
  //@field text
  $text = get_field('title');
  //@field text
  $subtitle = get_field('subtitle');
  //@field wysiwyg
  $about = get_field('about');
  //@field image
  $img = get_field('img');
?>
```
