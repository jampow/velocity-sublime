## Installation

Paste the repo folder into the `<SublimeText2Folder>/Packages`

## Snippets

*	``for`` - foreach ``#foreach( $var in $!{colection} ) ... #end``
*	``param`` - get url param ``$!{request.getParameter( _'someparameter'_ )}``
*	``if`` - if structure, without else ``#if(condition) ... #end``
*	``ifel`` - if else structure ``#if(condition) ... #else ... #end``
*	``ifparam`` - if some url param ``#if($!{request.getParameter( _'someparameter'_ )}) ... #end``
*	``else`` - only an else ``#else``
*	``set`` - set ``#set( $var = _value_ )``
*	``$`` - use variable ``$!{var}``
*	``!`` - html comment ``<!-- ... -->``