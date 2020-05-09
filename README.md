# `examplep` - Verbatim phrases and listings in LaTeX

`examplep` provides
sophisticated features for typesetting verbatim source code listings,
including the display of the source code and its compiled LaTeX or [METAPOST](https://www.ctan.org/pkg/metapost)
output side-by-side, with automatic width detection and enabled page breaks
(in the source), without the need for specifying the source twice. Special
care is taken so section, page and footnote numbers do not interfere with the
main document. For typesetting short verbatim phrases, a replacement for the
`\verb` command is also provided in the package, which can be used inside
tables and moving arguments such as footnotes and section titles. The
listings package is used for syntax highlighting.

The article ([eurotex_2005_examplep.pdf](eurotex_2005_examplep.pdf)) reviews the design decisions made
during the package development and also presents some interesting
implementation internals. examplep is compared to standard LaTeX packages
such as [listings](https://www.ctan.org/pkg/listings), [ltxdoc](https://www.ctan.org/pkg/ltxdoc), [sverb](https://www.ctan.org/pkg/sverb) and [moreverb](https://www.ctan.org/pkg/moreverb). The new `codep` package and its
accomanying Perl script, which provide a convenient interface to the `examplep`
package for authors of manuals, is also presented. With codep it is possible
to generate the source code, the LaTeX or METAPOST output and the compilable
example file onto the CD from a single source embedded into the appropriate
place of the `.tex` document file.

## About this repository

This is a repository building on the source found on  https://ctan.org/pkg/examplep (a5ab281101062e1e369462a6449eb43ad642a8c4) and on the author's homepage at <http://www.math.bme.hu/~pts/examplep_all.zip> (6a293ce44130e9d1eedfb427398292f6b829974e).
It is intended to collect issues and to offer a platform to submit improvements.

In case, the package can be improved, I will try to publish an updated version on CTAN.

## Alternatives

Following packages also have the same aim, but have certain drawbacks:

* [tcolorbox](https://www.ctan.org/pkg/tcolorbox) - nice boxes, but does not support floating environments
* [showexpl](https://ctan.org/pkg/showexpl) - does not fully support floating environments
* [latexdemo](https://ctan.org/pkg/latexdemo) - nice boxes, but does not support floating environments
* `tkzexample` (part of [tkz-doc](https://ctan.org/pkg/tkz-doc)) - nice boxes, but does not support floating environments
* `fancyvrb-ex` (part of [facnyvrb](https://ctan.org/pkg/fancyvrb)) - nice boxes, but does not support floating environments
* `cnltx-example`(part of [cnltx](https://www.ctan.org/pkg/cnltx)) - nice boxes, but does not support isolated floating environments
* [sverb](https://www.ctan.org/pkg/sverb) - offers the `demo` environment. Does not support isolated floating environments.
* `lstdoc` (part of [listings](https://www.ctan.org/pkg/listings)) - works inside the listings package, but causes issues at "normal" usage.
* `ydoc-expl` (part of [ydoc](https://www.ctan.org/pkg/ydoc))

See the [CTAN topic macro-demo](https://ctan.org/topic/macro-demo) for a complete list of all packages offering a similar functionality.

See <https://tex.stakexchange.com/q/19295/9075> for details and examples on some of these packges.

## License

The software is free software, covered by the GNU GPL v2.0 or later.
There is NO WARRANTY.
