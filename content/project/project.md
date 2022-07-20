---
# # Listing view
# view: compact

# # Optional banner image (relative to `assets/media/` folder).
# banner:
#   caption: ''
#   image: ''

widget: pages
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title: Projects
subtitle: ''

# Position of this section on the page
weight: 20

content:
  # Filter content to display
  filters:
    # The folders to display content from
    folders:
      - project
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  # Useful if you wish to show the first item in the Featured widget
  offset: 0
  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false
  
design:
  # Choose a listing view
  view: compact
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
---

Check out my recent blog posts below!