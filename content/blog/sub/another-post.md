+++
date = 2025-05-16T15:00:00Z
description = "My dick blah blah blahj article showcasing a custom Zola shortcode for embedding Streamable Videos into your pages."
draft = false
title = "Embed Streamable"

[extra]
# series = "Features"
toc = true

[taxonomies]
tags = []
+++
This is a another test post page for the firs post
<!-- more -->

## Streamable

### Usage

```rs
{{/* streamable(id="92ok4") */}}
```

- `id` - the video id (mandatory)
- `class` - a class to add to the &lt;div&gt; surrounding the iframe (optional)
- `title` - set alt title for the iframe (optional, defaults to "Streamable")

### Output

```html
{{ streamable(id="92ok4") }}
```

{{ streamable(id="92ok4") }}
