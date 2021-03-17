# reading note 04

### Links

HTML offers many of the conventional publishing idioms for rich text and structured documents, but what separates it from most other markup languages is its features for hypertext and interactive documents. This section introduces the link (or hyperlink, or Web link), the basic hypertext construct. A link is a connection from one Web resource to another. Although a simple concept, the link has been one of the primary forces driving the success of the Web.

A link has two ends -- called anchors -- and a direction. The link starts at the "source" anchor and points to the "destination" anchor, which may be any Web resource (e.g., an image, a video clip, a sound bite, a program, an HTML document, an element within an HTML document, etc.).

### Layout

One of the best ways to learn a technology is to have a specific use case you’re attempting to support or a particular problem you’re trying to solve. Toward that end, we’ll focus on a use case with a specific set of requirements.
Our use case consists of a Web App layout with some dynamic behavior. It will have fixed elements on the page such as a header, footer, navigation menu and sub-navigation, as well as a scrollable content section. Here are the specific layout requirements:

### Basic Layout

Header, footer, navigation menu, and sub-navigation all remain fixed on scroll
Navigation and sub-navigation elements occupy all vertical free space
Content section uses all remaining free space on the page and has a scrollable area

### Dynamic Behavior

Navigation menu only shows icons by default, but can be expanded to display text as well (and can then be collapsed to again show only icons)

### Layout Variations

Some pages have sub-navigation next to the navigation menu and some do not
