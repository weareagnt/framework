# TI-LMS

### Widget Helpers
Add the following helper classes to apply a specific style to the widget.

- widget--left -> Reduces the widget width to be 75% it's normal size and aligns it to the left.
- widget--right -> Reduces the widget width to be 25% it's normal size and aligns it to the right.
- widget--fullwidth -> Stretches widget width beyond it's normal size to be 100% of the screen width.
- widget--bg -> Applies a background color to the widget. The TI primary brand color is used. This class is often used with - - widget--fullwidth.
- widget--separator -> Applies a custom separator (horizontal rule) at the bottom of the widget.
- widget--nomargin -> Removes the default vertical spacing at the top of the widget.
- widget--nopadding -> Removes the default vertical spacing at the bottom of the widget.
- widget--center -> Centers the widget text including the title, subtitle, and CTA.


### Themed Widgets
Add the following custom classes to theme their respective widgets.

- hero-custom -> Hero Widget
- hero-custom hero-image-cover -> Hero Widget - Displays the hero image as a background image.
- hero-slider-custom -> Hero Slider Widget
- navbar-custom -> Navigation Widget
- single-column-custom -> Single Column Widget
- two-column-custom -> Two Column Widget
- three-column-custom -> Three Column Widget
- about-custom - About Widget
- featured-content-tiles-custom - Featured Content Tiles Widget
- featured-content-tiles-custom tiles-horizontal -> Featured Content Tiles Widget - Displays the individual tile content horizontally
- overlay-tiles-custom -> Overlay Tiles Widget
- catalog-custom -> Catalog Widget
- dashboard-access-custom -> Dashboard Access Widget


### Hero Widget
Hero images have no set constraints, but all should have a minimum height of 450px since that is the max height of the hero section container. Height of the image can be doubled to 900px for retina display. Additional image formatting varies based on the type of hero section implemented.

#### Contain
- Image is displayed to the right of the hero text mimicking a two column layout.
- Recommended aspect ratio is approximately 3/2, ie, 675 x 450px.
- Image will fill the smallest constraint which is typically the height of the container.
- Apply a transparency to the image during production because the section displays the primary brand color behind the image and text.
- Image is right aligned.
- Can be applied by adding the following classes to the hero widget: "hero-custom widget—fullwidth”.

#### Cover
- Image is displayed as a background behind the hero text.
- Recommended aspect ratio is approximately 3/1, ie, 1350 x 450px.
- Image will fill the largest constraint which is typically the width of the container. Image height will typically be cropped.
- If the hero section has text, a dark gradient overlay should be applied to the image during production.
- Image is centered.
- Can be applied by adding the following classes to the hero widget: "hero-custom hero-image-cover widget—fullwidth". I would recommend referencing the home page hero widget.
