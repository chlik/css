Compass Usage
=============

##Compass Modules
  - 1. reset
  - 2. css3
  - 3. layout
  - 4. typography
  - 5. utilities
  
'''css
@import "compass/reset";
'''
###CSS3 Modules
'' @import "compass/css3"; ''
- @include border-radius(5px);
- @include border-radius(5px 4px 3px 2px);
- @include border-corner-radius(top, left, 5px);
- @include opacity(0.5); 
- @include inline-block;


###Layout Modules
'' @import "compass/layout"; ''
- @include sticky-footer(54px); [sticky footer](http://compass-style.org/examples/compass/layout/sticky-footer/)
- @include stretch; [Stretching](http://compass-style.org/reference/compass/layout/stretching/)
