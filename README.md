# Snippets for CMS Made Simple HTML (Smarty) Templates

<img src="https://media.giphy.com/media/3osBLApyhtxmeYhgdy/giphy.gif" />

## Known Issues

To handle .tpl files in the same way as .html files, you should adjust the user settings as follows:
```json
 "files.associations": {
    "*.tpl": "html"
}
```

## Release Notes

### 1.0.0

Added the following snippets:

Snippet | Purpose
------------ | -------------
cb | creates a ```{content}``` block tag 
ci | creates a ```{conten_image}``` block tag
year | creates a ```{current_date}``` tag and ouputs the current year
literal | creates a opening an closing ```{literal}``` tag
literaljs | creates a opening an closing ```{literal}``` tag wrapped in a html ```<script>``` tag
breadcrumbs | ```{nav_breadcrumbs}```
include | creates a ```{include}``` tag
ifelse | smarty if else statement
foreach | smarty foreach loop
mailto | creates a ```{mailto}``` tag which encrypts an email addresss with javascript
cmshtml | html boilerplate file with useful tags that can be used for any CMS Made Simple website



Link to official CMS Made Simple [Website](https://www.cmsmadesimple.org/)

**Enjoy!**