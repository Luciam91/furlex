# Changelog

## v.0.2.1
* Add status code to %Furlex{} structure (thanks [abitdodgy](https://github.com/abitdodgy))
* Fix compatibility with Phoenix 1.3 (thanks, again, [abitdodgy](https://github.com/abitdodgy)!)

## v.0.2.0
* Support configuration for grouping colon-delimited keys into map structures
* Don't require explicitly configuring OpenGraph and TwitterCard tags in your app config.
* Enable adding custom tags under OpenGraph and TwitterCard parsers.

## v.0.1.3
* Add typespecs, better examples to documentation

## v.0.1.2
* Parse colon-separated OpenGraph and Twitter Card keywords into map structures
  - E.g. %{"twitter:app:id" => 123} becomes %{"twitter" => %{"app" => %{"id" => 123}}}

## v.0.1.1
* Fix test-breaking bug when included as hex dependency
* Add tags

## v.0.1.0
* Support unfurling oEmbed, Facebook Open Graph, Twitter Card, JSON-LD and other HTML meta tags.
* Extract canonical urls
