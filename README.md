# Project -Customise wordpress Essential grid gallery
 
## Use WordPress Essential Grid Gallery plugin. Free version

![Customise wordpress Essential grid gallery](https://dl.dropboxusercontent.com/s/cvl31fxzqr8kmh6/wp_essential_grid.jpg)

Essential Grid Gallery is a premium plugin for WordPress that allows you to build great looking image, video and audio galleries from various sources! Use the adapted WordPress gallery functionality, posts and pages, include albums built with other plugins like NextGen Gallery, connect to the big social media streams like Instagram, YouTube, Vimeo, Twitter, Flickretc. or build a complete custom Gallery grid. Our template library will give you example grids that will look outstanding on mobile devices too and are easy to configure and fill with your content!

Product Features:
>All-Purpose Usage
>Boxed, Full-Width, Full-Screen Layouts
>Adjustable Rows/Columns/Spacings
>Images, Youtube & Vimeo Video, HTML5 Self-Hosted Video, iFrame Content
>Content Sources: Post, Custom Post, Pages, WooCommerce, Gallery
>Various Animation Types & Preloaders
>Dozens Example Skins available
>Responsive & Mobile Optimized
>Visual Skin Editor: Build and Customize own Skins easily
>Easily Import / Export Skins
>Include Custom Skins with Plugin Install, One-Click Installer
>Custom Metas: Additional Options for Posts
>Custom Post Based Skin Modifications: Special rules for Posts
>Extensive Documentation & Tutorial Videos
>Customizable Transition Speed (Individual / Global)

###### Default available parameters
```
%title%
%post_id%
%excerpt%
%cat_list%
%tag_list%
%date%
%date_year%
%date_month%
%date_day%
....
```
###### How it works

1. Create custom php function in function.php and Assign.
2. Call do_shortcode in Item Skin Editor.

> functionsphp
```
function tp_custom_essgrid_shortcode( $atts ) {  
$value= '';
$p = shortcode_atts( array(  'id' => 0 ), $atts );
 /* Procedure here..
  YOU CAN GET values from WP_Query..
 */
 return $value;
}
add_shortcode( 'custom_essgrid_audio', 'tp_custom_essgrid_shortcode' );
```
> Gallery custom Text/HTML snippet
```
[custom_essgrid_audio id=%post_id%]
```

Visit Blog here. [Blog](https://www.jinlongcode.com/post/wordpress-essential-grid-custom-php-with-do_shortcode)
Contact us if you have problems. [link to JLCode!](https://jinlongcode.com)
