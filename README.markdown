# HTML5 input pseudo selectors
Copyright (c) 2009, Mike Taylor, http://miketaylr.com
MIT Licensed: http://www.opensource.org/licenses/mit-license.php

## Usage
<code>$(':search').whatever(); OR $(':input:search').whatever()</code>
selects all <code>&lt;input type="search"&gt;</code> elements, etc.

Thanks to Paul Irish and Ben Alman for non-medicated feedback!
And thanks again to Paul Irish for making it loopier.

## Unit Tests
http://miketaylr.com/test/qunit/html5pseudoselectors.html

### Note:
Rather than just function(elem){return type === "foo"} we use elem.getAttribute("foo") because unknown input types are treated as type=text.