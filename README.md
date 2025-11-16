# avro-wikipages

An example Avro knowledge base structure using GitHub wiki pages with a deep sidebar navigation tree.

## Overview

This repository demonstrates how to create a deeply nested sidebar navigation structure for GitHub wiki pages. The example shows an 11-level deep hierarchy:

```
aa
└── bb
    └── cc
        └── dd
            └── ee
                └── ff
                    └── gg
                        └── hh
                            └── jj
                                └── kk
                                    └── ll
```

## Files

- `Home.md` - Main wiki landing page
- `_Sidebar.md` - Sidebar navigation with nested structure
- `aa.md` through `ll.md` - Individual wiki pages for each level of the hierarchy

## Usage with GitHub Wiki

To use these files with a GitHub wiki:

1. Enable the wiki for your repository (Settings → Features → Wikis)
2. Clone the wiki repository: `git clone https://github.com/YOUR_USERNAME/YOUR_REPO.wiki.git`
3. Copy all `.md` files from this repository into the wiki repository
4. Commit and push the files to the wiki repository
5. Visit your wiki to see the deep sidebar navigation in action

## Sidebar Structure

The `_Sidebar.md` file uses proper indentation (2 spaces per level) to create the hierarchical structure. GitHub wiki automatically renders this as a collapsible tree navigation.

## Benefits

This structure allows for:
- Organizing complex documentation hierarchically
- Easy navigation through parent-child relationships
- Clear information architecture
- Support for very deep topic nesting (11+ levels demonstrated)

## Example Use Cases

- API documentation with nested resources
- Technical specifications with multiple subsections
- Learning paths with progressive topics
- Product documentation with feature hierarchies