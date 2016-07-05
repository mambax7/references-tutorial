# 8.0 Other

####Extra directory contents
The Extra directory contains at its root a PHP script called **clone.php**. This script allows you to clone the module.

> ![](../assets/info/stop.png) This script requires knowledge of PHP. Don't attempt to use it, if you're not proficient with PHP.

If you want to clone the module, place this script in the root of your site and run it.

Beforehand, make sure you have edited it to indicate the new name you want to give to the module.
 
####Other scripts in the Extra directory
In the subdirectory 

```
/modules/rss/plugins/ 
```

is a script entitled "**rssfit.references.php**", this script is useful if you use the unit RssFit module

In the subdirectory 

```
/modules/sitemap/plugins/ 
```

is a script entitled "**references.php**" 

If you use the "Sitemap" module, you can use this plugin to generate a map of your categories
 
####Customizing the appearance of accordions
If you have some knowledge of CSS, you can customize the appearance of accordions by editing the following file: 
```
/xoops/modules/references/js/css/accordion.css
```