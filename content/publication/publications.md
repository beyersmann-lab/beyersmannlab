---
title: My page
type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: My subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      filters:
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - section
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: citation
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
