**Important: This repo and gem are unmaintained! If you are interested in
maintaining, please contact me at <t_leitner@gmx.at>.**

# kramdown PDF converter

This is a converter for [kramdown](https://kramdown.gettalong.org) that uses
[Prawn](http://prawnpdf.org) to converter a kramdown document to PDF.

Note: Until kramdown version 2.0.0 this converter was part of the kramdown
distribution.


## Installation

~~~ruby
gem install kramdown-converter-pdf
~~~


## Usage

~~~ruby
require 'kramdown'
require 'kramdown/converter/pdf'

Kramdown::Document.new(text).to_pdf
~~~


## Development

Clone the git repository and you are good to go. You probably want to install
`rake` so that you can use the provided rake tasks.


## License

MIT - see the **COPYING** file.
