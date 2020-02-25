# DKTabLayout
Forked from [FlycoTabLayout](https://github.com/H07000223/FlycoTabLayout).

[![Download](https://api.bintray.com/packages/dueeeke/maven/dk-tablayout/images/download.svg)](https://bintray.com/dueeeke/maven/dk-tablayout/_latestVersion)
#### [中文版](https://github.com/dueeeke/dk-tablayout/blob/master/README_CN.md)

## Gradle

```groovy
    dependencies {
        implementation 'com.github.dueeeke:dk-tablayout:1.0.2'
    }
```

## Demo
|SlidingTabLayout|CommonTabLayout|SegmentTabLayout|
|:---:|:---:|:---:|
![](https://github.com/dueeeke/dk-tablayout/blob/master/preview_1.gif)|![](https://github.com/dueeeke/dk-tablayout/blob/master/preview_2.gif)|![](https://github.com/dueeeke/dk-tablayout/blob/master/preview_3.gif)

## Attributes

|name|format|description|
|:---:|:---:|:---:|
| tl_indicator_color | color |set indicator color
| tl_indicator_height | dimension |set indicator height
| tl_indicator_width | dimension |set indicator width
| tl_indicator_margin_left | dimension |set indicator margin,invalid when indicator width is greater than 0.
| tl_indicator_margin_top | dimension |set indicator margin,invalid when indicator width is greater than 0.
| tl_indicator_margin_right | dimension |set indicator margin,invalid when indicator width is greater than 0.
| tl_indicator_margin_bottom | dimension |set indicator margin,invalid when indicator width is greater than 0.
| tl_indicator_corner_radius | dimension |set indicator corner radius
| tl_indicator_gravity | enum |set indicator gravity TOP or BOTTOM.
| tl_indicator_style | enum |set indicator style NORMAL or TRIANGLE or BLOCK
| tl_underline_color | color |set underline color
| tl_underline_height | dimension |set underline height
| tl_underline_gravity | enum |set underline gravity TOP or BOTTOM
| tl_divider_color | color |set divider color
| tl_divider_width | dimension |set divider width
| tl_divider_padding |dimension| set divider paddingTop and paddingBottom
| tl_tab_padding |dimension| set tab paddingLeft and paddingRight
| tl_tab_space_equal |boolean| set tab space equal
| tl_tab_width |dimension| set tab width
| tl_textSize |dimension| set text size
| tl_textSelectSize |dimension| set text select size
| tl_textSelectColor |color| set text select color
| tl_textUnselectedColor |color|  set text unselect color
| tl_textBold |boolean| set text is bold 
| tl_iconWidth |dimension| set icon width(only for CommonTabLayout)
| tl_iconHeight |dimension|set icon height(only for CommonTabLayout)
| tl_iconVisible |boolean| set icon is visible(only for CommonTabLayout)
| tl_iconGravity |enum| set icon gravity LEFT or TOP or RIGHT or BOTTOM(only for CommonTabLayout)
| tl_iconMargin |dimension| set icon margin with text(only for CommonTabLayout)
| tl_indicator_anim_enable |boolean| set indicator support animation(only for CommonTabLayout)
| tl_indicator_anim_duration |integer| set indicator animation duration(only for CommonTabLayout)
| tl_indicator_bounce_enable |boolean| set indicator aniamtion with bounce effect(only for CommonTabLayout)
| tl_indicator_width_equal_title |boolean| set indicator width same as text(only for SlidingTabLayout)