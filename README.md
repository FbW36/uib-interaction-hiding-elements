# Interaction: hiding elements

It is good to use both `opacity` and `visibility` when creating transitions.

`opacity` can be animated nicely. The issue is though that the user can still interact with an element that has `opacity: 0;` which can cause unexcpected results.

`visibility: hidden;` will not allow interactions, but cannot be nicely animated.

`display: block;` cannot be animated, so we don't use it when creating fade in animations.