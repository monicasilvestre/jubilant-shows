# totalboots4
Basic HTML page, using Bootstrap 4.
I'm using TotalJobs brand, as an example, for demonstrating what can be achieved with the new bootstrap.

Biggest changes vs Bootstrap 3:
  - Dropped IE8, IE9, and iOS 6 support. v4 is now only IE10+ and iOS 7+. For sites needing either of those, use v3
  - Has official support for Android v5.0 Lollipop’s Browser and WebView;
  - Flexbox is enabled by default: makes it easier to design flexible responsive layout structure without having to use floats or positioning; 
  - Mobile first;
  - Switched from LESS to SASS;
  - Default size unit is now 'rem', not 'px'; rem scales easier across device sizes, but px is still used for media queries and grid behaviour;
  - Updated responsive grid system, now using flexbox: 
      .col- (extra small devices - screen width less than 576px)
      .col-sm- (small devices - screen width equal to or greater than 576px)
      .col-md- (medium devices - screen width equal to or greater than 768px)
      .col-lg- (large devices - screen width equal to or greater than 992px)
      .col-xl- (xlarge devices - screen width equal to or greater than 1200px)- Responsive images .img-fluid 
  - Most of the existent components have been rewritten in flexbox.
  - Jumbotron: a big grey box for calling extra attention to some special content or information;
  - Cards replace panels, wells and thumbnails;  
  - Dropped the Glyphicons (use https://glyphicons.com/ or Font Awesome);
  - Accordion using class .collapse;
  - Carousel slideshows;
  - Modal component: popup window;
  - Scrollspy: jump to a section;
  - Album;
  - Utilities: spacing shorcuts (margin & padding) https://getbootstrap.com/docs/4.0/utilities/borders/
  - New classes: img-fluid, btn-group, badge, progress-bar, pagination;
  - New methods: popover();

  More info: https://getbootstrap.com/docs/4.0/migration/
