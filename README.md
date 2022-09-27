# page-limit
A macro to introduce a user-set page limit for LaTeX projects. To use this macro, include this file in your LaTeX project and include the following two lines in your document's preamble:

```
\include{page-limit}
\pagelimit{20}
```

The `\pagelimit` command must be used in the preamble, may not be used more than once per document, and does exactly what you expect - it sets the page limit to the given argument.
