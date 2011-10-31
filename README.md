# Soup

Useful clojurescript macros.

## Namespaces and macros

### me.panzoo.soup.macros

#### defslurp

`(def name (slurp uri))` but at compile time.

#### timeout

Execute forms in order with a time delay between each.

### me.panzoo.soup.macros.phantom

For use with [phantomjs](http://phantomjs.org).

#### passert

An assert macro for use with phantomjs.
