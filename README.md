# Alternative Text Selection Behavior

[](https://github.com/user-attachments/assets/8f352220-b14f-4230-9c8b-49ffe31b5beb)

[Demo (desktop browser recommended)](https://tastenbier.github.io/alternative-text-selection/index.html)

Drag-selecting text with a mouse from a box with overflow scrolling can be
annoying. The overflow only starts scrolling once you reach the end of the box,
requiring you to 'blindly' select text. Here are some different approaches to
text selection.

## Disclaimer

You probably shouldn't implement this on your website and hijack the default
browser behavior. Some people do this with browser scrolling behavior, and it is
almost always a bad idea. Stop doing this. This is just an unpolished proof of
concept to explore the feel of different selection behaviors. This should be
implemented in the browser itself (if at all).

However, there are some janky edge cases and this behavior isn't suitable for
most other overflow scrolling scenarios. So this will probably never be more
than just an idea.
