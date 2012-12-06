## Installation

Paste the repo folder into the `<SublimeText2Folder>/Packages`

## Snippets

*	``for`` - foreach ``#foreach( $var in $!{colection} ) ... #end``
*	``param`` - get url param ``$!{request.getParameter( 'someparameter' )}``
*	``if`` - if structure, without else ``#if(condition) ... #end``
*	``ifel`` - if else structure ``#if(condition) ... #else ... #end``
*	``ifparam`` - if some url param ``#if($!{request.getParameter( 'someparameter' )}) ... #end``
*	``else`` - only an else ``#else``
*	``set`` - set ``#set( $var = _value_ )``
*	``ready`` - gets the content of file ``$_reader.read("path/to/file.ext")``
*	``$`` - use variable ``$!{var}``
*	``!`` - html comment ``<!-- ... -->``
*	``vm`` - velocity head ``#!vm;utf-8``