FeatureDoc
==========

The intent is to convert `.feature` files (in *Gherkin* notation) and make *slightly* more pretty-printable output, marked up with [Markdown syntax](http://daringfireball.net/projects/markdown/syntax). These markdown files can then be included in documentation, perhaps by further processing them with Doxygen.

## Example output

Scenario: **Multiple Givens**

 *Given* one thing<br>
    *And* another thing<br>
    *And* yet another thing<br>
    *When* I open my eyes<br>
    *Then* I see something<br>
      *But* I don't see something else<br>
