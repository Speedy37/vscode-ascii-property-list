# Old-Style ASCII Property Lists

Add Old-Style ASCII Property Lists language support.

Language reference: https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/PropertyLists/OldStylePlists/OldStylePLists.html.

Also add support for an extended version of ASCII property list that supports:

 - Case insensitive `\UXXXX` string character encoding
 - Array of naturals (`[0, 2]`)
 - Custom classes (`@myclassname{ myproperty = "value" ; }`)
 - Constants (`YES`, `NO`)
