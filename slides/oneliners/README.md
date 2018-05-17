# Oneliners

These slides use the [`beamer-solarized`] theme from [pandoc-starter].

[`beamer-solarized`]: https://github.com/jez/pandoc-starter/tree/master/beamer-solarized
[pandoc-starter]: https://github.com/jez/pandoc-starter

See the [`Makefile`](Makefile) for usage information.

```make
# ===== Usage ================================================================
#
# NOTE:
#   When running these commands at the command line, replace $(TARGET) with
#   the actual value of the TARGET variable.
#
#
# make                  Compile all *.md files to PDFs
# make <filename>.pdf   Compile <filename>.md to a PDF
# make <filename>.tex   Generate the intermediate LaTeX for <filename>.md
#
# make view             Compile $(TARGET).md to a PDF, then view it
# make again            Force everything to recompile
#
# make clean            Get rid of all intermediate generated files
# make veryclean        Get rid of ALL generated files:
#
# make print            Send $(TARGET).pdf to the default printer:
#
# ============================================================================
```
