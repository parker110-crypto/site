# Jekyll Blog with Author Metadata

## Author Metadata Feature

This Jekyll site supports rich author metadata for blog posts.

### Adding Author Information

In your blog post's front matter, you can specify author details:

```yaml
---
layout: post
title: "My Blog Post"
author:
  name: "John Doe"
  bio: "Software developer and tech enthusiast"
  email: "john.doe@example.com"
  twitter: "@johndoe"
---
```

### Default Author

If no author is specified, the site's default author (set in `_config.yml`) will be used.

### Features
- Per-post author metadata
- Default site-wide author
- Displayed on post pages and index
- Flexible and extensible