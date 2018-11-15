# nojQuery Code Snippets

A bunch of snippets to easily migrate to ES6 Vanilla Js from jQuery.

The snippets are accessible by typing "v" followed up by the jQuery function you need.

![Image of Snippets](https://github.com/Nkzq/no-jQuery-snippets/blob/master/images/snippets.png?raw=true)

## Snippets

### Ajax

Trigger | Description
--- | ---
vajax | Provides a JavaScript interface for accessing and manipulating parts of the HTTP pipeline, such as requests and responses.

### Effects

Trigger | Description
--- | ---
vfadeIn | Display the matched elements by fading them using opacity.
vhide | Hide the matched elements.
vshow | Show the matched elements.

### Elements

Trigger | Description
--- | ---
vaddClass | Adds the specified class(es) to each of the set of matched elements.
vafter | Insert content, specified by the parameter, after each element in the set of matched elements.
vappend | Insert content, specified by the parameter, to the end of each element in the set of matched elements.
vbefore | Insert content, specified by the parameter, before each element in the set of matched elements.
vchildren | Get the children of each element in the set of matched elements, optionally filtered by a selector.
vclone | Create a deep copy of the set of matched elements.
vcontains | Check to see if a DOM element is a descendant of another DOM element.
vcontainsSelector | Get the descendants of each element in the current set of matched elements, filtered by a selector, jQuery object, or element.
vcss | Get the computed style properties for the first element in the set of matched elements.
veach | Iterate over a jQuery object, executing a function for each matched element.
vempty | Remove all child nodes of the set of matched elements from the DOM.
vfilter | Reduce the set of matched elements to those that match the selector or pass the function's test.
vfind | Returns a list of the elements within the document (using depth-first pre-order traversal of the document's nodes) that match the specified group of selectors.
vfindChild | Get the descendants of each element in the current set of matched elements, filtered by a selector, jQuery object, or element.
vgetAttr | Get the value of an attribute for the first element in the set of matched elements.
vhasClass | Determine whether any of the matched elements are assigned the given class.
vhtml | Get the HTML contents of the first element in the set of matched elements.
vis | Check the current matched set of elements against a selector, element, or jQuery object and return true if at least one of these elements matches the given arguments.
vnext | Get the immediately following sibling of each element in the set of matched elements. If a selector is provided, it retrieves the next sibling only if it matches that selector.
voffset | Get the current coordinates of the first element in the set of matched elements, relative to the document.
voffsetParent | Get the closest ancestor element that is positioned.
vouterHeight | Get the current computed outer height (including padding, border, and optionally margin) for the first element in the set of matched elements.
vouterHeightMargin | Get the current computed outer height (including padding, border, and optionally margin) for the first element in the set of matched elements.
vouterHtml | Get the outer HTML contents of the first element in the set of matched elements.
vouterWidth | Get the current computed outer width (including padding, border, and optionally margin) for the first element in the set of matched elements.
vouterWidthMargin | Get the current computed outer width (including padding, border, and optionally margin) for the first element in the set of matched elements.
vparent | Get the parent of each element in the current set of matched elements, optionally filtered by a selector.
vposition | Get the current coordinates of the first element in the set of matched elements, relative to the offset parent.
vpositionvp | Get the current coordinates of the first element in the set of matched elements, relative to viewport.
vprepend | Insert content, specified by the parameter, to the beginning of each element in the set of matched elements.
vprev | Get the immediately preceding sibling of each element in the set of matched elements. If a selector is provided, it retrieves the previous sibling only if it matches that selector.
vremove | Remove the set of matched elements from the DOM.
vremoveClass | Remove a single class, multiple classes, or all classes from each element in the set of matched elements.
vreplace | Replace each element in the set of matched elements with the provided new content and return the set of elements that was removed.
vsetAttr | Set one or more attributes for the set of matched elements.
vsetHtml | Set the HTML contents of each element in the set of matched elements.
vsetStyle | Set one or more CSS properties for the set of matched elements.
vsiblings | Get the siblings of each element in the set of matched elements, optionally filtered by a selector.
vtext | Get the combined text contents of each element in the set of matched elements, including their descendants.
vtoggleClass | Add or remove one or more classes from each element in the set of matched elements, depending on either the class's presence or the value of the state argument.

### Events

Trigger | Description
--- | ---
voff | Remove an event handler.
von | Bind an event handler.
vready | Specify a function to execute when the DOM is fully loaded.
vtrigger | Execute all handlers and behaviors attached to the matched elements for the given event type.

### Utils

Trigger | Description
--- | ---
vbind | Takes a function and returns a new one that will always have a particular context.
vinArray | Search for a specified value within an array and return its index (or -1 if not found).
visArray | Determine whether the argument is an array.
vmap | Translate all items in an array or object to new array of items.
vnow | Return a number representing the current time.
vparseHtml | Parses a string into an array of DOM nodes.
vparseJson | Takes a well-formed JSON string and returns the resulting JavaScript value.
vtrim | Remove the whitespace from the beginning and end of a string.
vtype | Determine the internal JavaScript [[Class]] of an object.

Thanks to [You Might Not Need jQuery](http://youmightnotneedjquery.com/)