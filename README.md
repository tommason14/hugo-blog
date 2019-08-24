# Personal Site

Using the [hugo-resume](https://github.com/eddiewebb/hugo-resume) theme developed by Eddie Webb, this is my personal
site.

Slight tweaks to the theme:
- added css variables in themes/static/css
- added some liquid tags to not show publications if `featured: false`
  in YAML header
- Now description set in config.toml is shown under the first heading
- Added repo field in experience.json. Note this must be set, with html
  generated if the field is not "".
- For now, commented out the 'wait there's more' bit in layouts/partials/sectionSummary.html
