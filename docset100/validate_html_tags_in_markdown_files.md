# How to validate html tags in markdown files

In markdown files, we can write any html tags.
But we need validate some html tags in markdown files.

E.g. <a href="http://dotnet.github.io/docfx/tutorial/validate_your_markdown_files.html">document</a> should not be write in markdown files,
because we should write it in markdown syntax: [document](http://dotnet.github.io/docfx/tutorial/validate_your_markdown_files.html).  
Branch: `htmltag1` will validate this case.

In advance, some tags with some attributes are valid, otherwise they are invalid.
For example, <a>a without id is invalid</a> but <a id="some id">a with id is valid</a>, because we cannot write such tags in markdown syntax.  
Branch: `htmltag2` will validate this case.
