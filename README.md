# About detoxified-dark

Just another pseudo-responsive theme for Cryogen by [knows-the-cost-of-nothing](https://github.com/knows-the-cost-of-nothing). 

Example page: [irrelevancy universe](https://knows-the-cost-of-nothing.github.io/).

## (Non-)Features

* Tries to focus on textual content
* Valid markup (W3C)
* "WCAG 2 AAA" compliant template colors
* No template images
* No grids / (flex)boxes
* No (obligatory) JS
* No class/id usage for styling
* No disqus support (compared to Cryogen default theme) (-> JS)
* No syntax highlighting (compared to Cryogen default theme) (-> JS)
* No klipse integration (compared to Cryogen default theme) (-> JS)


## Usage

Add/modify following keys in `content/config.edn`:

1. Modify the `:theme` key ("detoxified-dark").
2. Add the key `:site-language` (e.g. "en", will be used as HTML lang attribute).
3. Add the key `:date-output-format` (e.g. "dd/MM/yyyy", see [selmer documentation](https://github.com/yogthos/Selmer#date) for more details).
4. Add the key `:footer-notice` (e.g. "Copyleft irrelevance", you can use any HTML string here)
