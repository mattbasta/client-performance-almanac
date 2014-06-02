# Conclusion

## Proverbs


## Notable Tickets

Throughout this book, I've made note of many tickets in bug trackers for different browser vendors. This section is simply a collection of those tickets, along with a summary of each of the issues.

### Firefox

- **Bug 730101:** Implement prerendering support http://bugzil.la/730101
- **Bug 856375:** Implement WebP support http://bugzil.la/856375


### Chromium

- **Issue 128055:** This issue prevents CSS properties from using hashes to reference individual components of an SVG image. This functionality is available in IE9 and up as well as Firefox. http://crbug.com/128055
- **Issue 131368:** Chromium does not respect CORS header caching for longer than ten minutes. http://crbug.com/131368
- **Issue 312327:** This issue causes subresource requests not to be used when an asset is requested in a document. This prevents subresource requests from being useful. http://crbug.com/312327


## Mentioned Tools

- CSS sprite tool: Spritegen - http://spritegen.website-performance.org/
- CSS sprite tool: Spritificator - http://potch.me/projects/spritificator/
- CSS minification tool: clean-css - https://github.com/GoalSmashers/clean-css
- CSS minification tool: mincss - https://mincss.readthedocs.org/
- JavaScript minifier: JSMin - http://www.crockford.com/javascript/jsmin.html
- JavaScript minifier: Closure Compiler - https://developers.google.com/closure/compiler/
- JavaScript minifier: UglifyJS2 - https://github.com/mishoo/UglifyJS2
- JavaScript parser: esprima - https://github.com/ariya/esprima
- JavaScript parser: acorn - https://github.com/marijnh/acorn
- JavaScript code generator: escodegen - https://github.com/Constellation/escodegen


## Glossary

### CSS

Declaration
: A declaration is an item within a rule set that applies a given property to the set of matched elements. E.g.: `color: red;`

Rule Set
: A rule set is a selector and zero or more declarations wrapped in curly braces. E.g.: `.myElement {font-weight: bold;}`

Selector
: A selector is the string which describes which elements a rule set applies to. E.g.: `#myElement .withAClass p`


## Thanks

I'd like to use this space to thank my friends, family, and past and present coworkers for helping me to make this book possible. So many people have been supportive, offered advice or consultation, helped with fact-checking, proofreading, and more, and made contributions to improve this work.

In particular, I'd like to thank:

Chris Van (@cvanw)
: Many thanks to Chris for his incessant focus on performance and attention to detail. Your pull requests and comments, as well as your ever-inquisitive nature have driven me to make this book as thorough and exhaustively accurate as I could possibly make it.