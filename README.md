# Vimrc-Macros
A number of macro assignments that I have found quite usefull.

Just so there's no confusion, my .vimrc has:
```vim
set tabstop=4
set expandtab
```
and no softtab setting.
I use the "z buffer to hold things, so that could overwrite something if you store
things in there normally.
I haven't tried it with different settings. Let me know if you run into issues.

## HTML Tag Maker:
This would take a line `div id = "my-id"` and produce this:
```html
<div id = "my-id">
    <!--It leaves the cursor indented by 4 spaces-->
</div>
```
## Curly Braces Code Block Maker:
This will take a line such as `function my_heart_will_go_on()` and produce this:
```php
function my_heart_will_go_on() {
    //It leaves the cursor indented by 4 spaces
}
```
## PHP Tag Maker
This will open and close a php tag after your cursor
It doesn't go ahead and open up the tags as I find 
myself using inline php as much as block:
```php
<?php //I leaves your cursor here ?>
```
## Universal Opener
This opens whatever. Just a general purpose. Not sure
if it's worth it yet. We'll see if it stays. Anyway,it
takes this `<?php ?>` or this `{}`and makes this:
```php
<?php 
    //It leaves the cursor here
?>
```
or this:
```php
{
    //It leaves the cursor here
}

