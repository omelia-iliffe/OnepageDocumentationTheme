A One Page Documentation theme by Harry Iliffe
Using bootstrap 4.2


This theme includes tools for display pictures

#### Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-remote-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
plugins:
  - jekyll-remote-theme
remote_theme: harryiliffe/OnepageDocumentationTheme
```

And then execute:

    $ bundle

#### Usage

Add pages to the folder `_pages`
each page needs front matter like this

```yaml
onepage-id: 1
title: "Another Page"
description: "with description as well"
nav-color: customcolor1
```

`_config.yml`

```yaml
title: "Onepage Documentation"
description: "Theme by Harry Iliffe"


# Probably dont edit this stuff!
include: ["_pages"]
defaults:
  -
    scope:
      path: ""
    values:
      layout: "default"
      hidden: false

plugins:
  - jekyll-remote-theme
remote_theme: harryiliffe/OnepageDocumentationTheme

```
