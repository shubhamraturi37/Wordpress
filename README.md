# wordpress custom Template
## Step 1. Create a new php file and save it to your theme directory `my_template.php`
## Step 2. put the below code in your `my_template.php` file 
``` php
<?php
/**
 * Template Name: my template
 * author: shubham
 */
?>
```
### if you wants to add header and footer then use
``` php
<?php
/**
 * Template Name: my template
 * author: shubham
 */
get_header();
?>
<html>
    <body>
        <h3>this is html content</h3>
    </body>
</html>
<?php 
get_footer();
?>
```
