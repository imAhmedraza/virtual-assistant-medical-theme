# Theme Architecture

The theme separates presentation code from editable WordPress content.

- Homepage copy: WordPress/SCF-backed settings.
- Services: vam_service custom post type with SCF fields.
- Blog: native WordPress Posts and Gutenberg.
- Contact: native WordPress admin-post handler.
- Visual design: PHP templates, CSS and JavaScript.
- Future code changes: Git/GitHub, with staging before production.

The React/Vite project remains the original visual/design reference.
