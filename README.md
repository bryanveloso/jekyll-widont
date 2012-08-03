# jekyll-widont

Take the [widows](http://en.wikipedia.org/wiki/Widows_and_orphans) out of your
[Jekyll](https://github.com/mojombo/jekyll).

# Installation

Create a `_plugins` directory in your Jekyll installation if one doesn't
already exist. Throw `widont.rb` in there and make sure to restart Jekyll if
it's currently running.

# Usage

Apply the filter using Liquid's filter syntax, `|`, to any string that you
want to process.

  <h1>{{ page.title | widont }}</h1>
  <div class="entry-content">{{ page.content | widont }}</div>

# Special Thanks

Special thanks to [Steve Smith](https://github.com/orderedlist) for the
regular expression he joyfully referred to as "... the best widow-removing
regex ever. It's epic."
