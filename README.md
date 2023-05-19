# underlined
Simple Mistune plug-in  that turns `_` Markdown tags into `<ul>` instead of `<em>` HTML tags

## Use

```Python
from mistune import Markdown
from underlined import underlined

md = 'this _text_ is underlined'
parser = Markdown()
underlined(parser)
html = parser(md)
```

> this \<ul>text\</ul> is underlined