# page-limit
A macro to introduce a user-set page limit for LaTeX projects. To use this macro, include the file `page-limit.tex` in your LaTeX project (e.g. in the root folder) and include the following two lines in your document's preamble:

```
\include{page-limit}
\pagelimit{20}
```

The `\pagelimit` command must be used in the preamble, may not be used more than once per document, and does exactly what you expect - it sets the page limit to the given argument.

If compiling your document breaches the set page limit, it will report a single error warning you that you've gone over your set limit and politely suggest you either edit the document's content to fit within the page limit or change the page limit as suitable. It will still render any pages that go over the user-set limit, leaving them untouched.
