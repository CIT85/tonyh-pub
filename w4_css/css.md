# Units and Values
-dont need to set the width of the body, it should default to 100%
*width* at 100% is more desirable
-body grows with the content.
*height*- set min-height to 100vh; so it grows with the content but it is a full page.
## devTools box model
-*ctrl+shift+I* to open
-*Computed* tab, shows each layer and size.
-**always** want to bring out the box model to see what's going on with your element.
### Font-family fall back
-*How fall back works*
:can list more than one font in case one is not available. uses it in order.
-*How quotes work*
:**Need** quotes around font family that has a space in between its name.
#### Pseudo class
-Keyword added to selectors to specifies the current state of the element class.
-Enabling styling based on certain conditions
-**How specificity and order works with links**:
    -determines which style rule is applied
    -*EX:*-:focus, :visited, :hover, and :active
    -the order of how they are written still matters
        -CSS applies the most specific rule last
