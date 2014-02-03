# ez-query-replace

ez-query-replace is a simple wrapper around `query-replace' that adds
a default search term, and allows you to conveniently replay old
replacements.

## Changelog

### v0.3

If the region is active when ez-query-replace is called, we deactivate
it after readings its contents. The active region just gets in the way
when you're replacing values.

### v0.2

Improved the minibuffer prompt: say what we're replacing when we do
the replacement.

### v0.1

Initial release.
