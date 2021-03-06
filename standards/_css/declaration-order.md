---
order: 130
---

### Declaration order

**Recommended** only. During the course of development this might not be realistic. Try to keep the following recommendations in mind.

Related property declarations should be grouped together following the order:

1.  Positioning
2.  Box model
3.  Typographic
4.  Visual

Positioning comes first because it can remove an element from the normal flow of the document and override box model related styles. The box model comes next as it dictates a component's dimensions and placement.

Everything else takes place _inside_ the component or without impacting the previous two sections, and thus they come last.

For a complete list of properties and their order, please see [Recess](http://twitter.github.com/recess).