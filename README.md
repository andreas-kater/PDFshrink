# Shrinking PDFs

run `./shrinkpdf.sh input.pdf output.pdf` in terminal

## Insalling ghostscript

If you don't have it installed already, you may need to install ghostscript.
This can be done by running:

`brew install ghostscript`

## Specifying the quality

The default resolution is 72 DPI. You can adjust this by entering a third
argument, like so:

`./shrinkpdf.sh input.pdf output.pdf 90`

## Thanks to Alfred Klomp

Alfred Klmop is the original author of the shrinkpdf script. Many thanks for this
useful script.
