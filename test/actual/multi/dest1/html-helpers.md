# html-helpers.md output

## Content


<h2>HTML list helpers.</h2>
<h3>{{ul}} helper</h3>
<ul class="nav"><li>
  one
</li>
<li>
  two
</li>
<li>
  three
</li></ul>

<ul class="nav"><li>
  <a href="one">two</a>
</li>
<li>
  <a href="three">four</a>
</li>
<li>
  <a href="five">size</a>
</li></ul>

<h3>{{ol}} helper</h3>
<ol class="nav"><li>
  one
</li>
<li>
  two
</li>
<li>
  three
</li></ol>

<ol class="nav"><li>
  <a href="one">two</a>
</li>
<li>
  <a href="three">four</a>
</li>
<li>
  <a href="five">size</a>
</li></ol>

<h3>{{link}} helper</h3>
<p><a href="">helpers.js</a>
<a href="http://github.com">GitHub</a>
<a href="http://github.com">GitHub</a></p>




## Debug Info
``` json
{ filename: 'html-helpers.md',
  extname: '.md',
  dest: 'test/actual/multi/dest1/html-helpers.md',
  basename: 'html-helpers',
  _page: 'all',
  dirname: 'test/actual/multi/dest1',
  moreLinks: 
   [ { url: 'one', text: 'two' },
     { url: 'three', text: 'four' },
     { url: 'five', text: 'size' },
     [length]: 3 ],
  data: 
   { text: 'helpers.js',
     links: [ 'one', 'two', 'three', [length]: 3 ],
     moreLinks: 
      [ { url: 'one', text: 'two' },
        { url: 'three', text: 'four' },
        { url: 'five', text: 'size' },
        [length]: 3 ] },
  links: [ 'one', 'two', 'three', [length]: 3 ],
  assets: '../../assets',
  ext: '.md',
  pageName: 'html-helpers.md',
  page: '\n{{#markdown}}\n\n## HTML list helpers.\n\n### \\{{ul}} helper\n{{#ul links class="nav"}}\n  {{.}}\n{{/ul}}\n\n{{#ul moreLinks class="nav"}}\n  <a href="{{url}}">{{text}}</a>\n{{/ul}}\n\n### \\{{ol}} helper\n{{#ol links class="nav"}}\n  {{.}}\n{{/ol}}\n\n{{#ol moreLinks class="nav"}}\n  <a href="{{url}}">{{text}}</a>\n{{/ol}}\n\n### \\{{link}} helper\n{{_link url text}}\n{{_link \'http://github.com\' \'GitHub\'}}\n{{_link \'http://github.com\' \'GitHub\' \'nav-link\'}}\n\n{{/markdown}}{{! /end markdown}}\n',
  text: 'helpers.js',
  src: 'test/fixtures/pages/html-helpers.hbs',
  pagename: 'html-helpers.md' }
```


### "{{#each pages}}" Links
[example](example.md)
[alert](alert.md)
[collections-categories](collections-categories.md)
[collections-categories2](collections-categories2.md)
[collections-tags-2](collections-tags-2.md)
[collections-tags](collections-tags.md)
[complex](complex.md)
[context](context.md)
[debug-helpers](debug-helpers.md)
[deep-nested-layouts](deep-nested-layouts.md)
[assets](assets.md)
[gist-helper](gist-helper.md)
[helpers](helpers.md)
[home](home.md)
[html-helpers](html-helpers.md)
[md-helper](md-helper.md)
[nested-layouts](nested-layouts.md)
[no-layout-none](no-layout-none.md)
[no-layout](no-layout.md)
[page](page.md)
[simple3](simple3.md)



### {{#each pages}} "this" context

#### example.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/example.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: example.md
this.pagename: example.md
this.basename: example
this.extname:  .md
this.ext:      .md

#### alert.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/alert.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: alert.md
this.pagename: alert.md
this.basename: alert
this.extname:  .md
this.ext:      .md

#### collections-categories.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/collections-categories.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: collections-categories.md
this.pagename: collections-categories.md
this.basename: collections-categories
this.extname:  .md
this.ext:      .md

#### collections-categories2.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/collections-categories2.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: collections-categories2.md
this.pagename: collections-categories2.md
this.basename: collections-categories2
this.extname:  .md
this.ext:      .md

#### collections-tags-2.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/collections-tags-2.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: collections-tags-2.md
this.pagename: collections-tags-2.md
this.basename: collections-tags-2
this.extname:  .md
this.ext:      .md

#### collections-tags.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/collections-tags.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: collections-tags.md
this.pagename: collections-tags.md
this.basename: collections-tags
this.extname:  .md
this.ext:      .md

#### complex.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/complex.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: complex.md
this.pagename: complex.md
this.basename: complex
this.extname:  .md
this.ext:      .md

#### context.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/context.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: context.md
this.pagename: context.md
this.basename: context
this.extname:  .md
this.ext:      .md

#### debug-helpers.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/debug-helpers.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: debug-helpers.md
this.pagename: debug-helpers.md
this.basename: debug-helpers
this.extname:  .md
this.ext:      .md

#### deep-nested-layouts.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/deep-nested-layouts.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: deep-nested-layouts.md
this.pagename: deep-nested-layouts.md
this.basename: deep-nested-layouts
this.extname:  .md
this.ext:      .md

#### assets.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/assets.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: assets.md
this.pagename: assets.md
this.basename: assets
this.extname:  .md
this.ext:      .md

#### gist-helper.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/gist-helper.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: gist-helper.md
this.pagename: gist-helper.md
this.basename: gist-helper
this.extname:  .md
this.ext:      .md

#### helpers.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/helpers.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: helpers.md
this.pagename: helpers.md
this.basename: helpers
this.extname:  .md
this.ext:      .md

#### home.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/home.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: home.md
this.pagename: home.md
this.basename: home
this.extname:  .md
this.ext:      .md

#### html-helpers.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/html-helpers.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: html-helpers.md
this.pagename: html-helpers.md
this.basename: html-helpers
this.extname:  .md
this.ext:      .md

#### md-helper.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/md-helper.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: md-helper.md
this.pagename: md-helper.md
this.basename: md-helper
this.extname:  .md
this.ext:      .md

#### nested-layouts.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/nested-layouts.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: nested-layouts.md
this.pagename: nested-layouts.md
this.basename: nested-layouts
this.extname:  .md
this.ext:      .md

#### no-layout-none.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/no-layout-none.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: no-layout-none.md
this.pagename: no-layout-none.md
this.basename: no-layout-none
this.extname:  .md
this.ext:      .md

#### no-layout.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/no-layout.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: no-layout.md
this.pagename: no-layout.md
this.basename: no-layout
this.extname:  .md
this.ext:      .md

#### page.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/page.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: page.md
this.pagename: page.md
this.basename: page
this.extname:  .md
this.ext:      .md

#### simple3.md
this.assets:   ../../assets
this.dest:     test/actual/multi/dest1/simple3.md
this.absolute:
this.dirname:  test/actual/multi/dest1
this.filename: simple3.md
this.pagename: simple3.md
this.basename: simple3
this.extname:  .md
this.ext:      .md


### {{#each pages}}

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md

#### html-helpers.md
page.assets:   ../../assets
page.dest:     test/actual/multi/dest1/html-helpers.md
page.absolute: 
page.dirname:  test/actual/multi/dest1
page.filename: html-helpers.md
page.pagename: html-helpers.md
page.basename: html-helpers
page.extname:  .md
page.ext:      .md


### {{#each pages}} "page" context

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

#### html-helpers.md
assets:        ../../assets
dest:          
absolute:      test/actual/multi/dest1/html-helpers.md
dirname:       test/actual/multi/dest1
filename:      html-helpers.md
pagename:      html-helpers.md
basename:      html-helpers
extname:       .md
ext:           .md

