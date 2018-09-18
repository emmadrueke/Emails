# Emails
this is me testing out my new mjml skills
by coding up some emails.

## Development
  1. Each email gets it's own directory
  1. Run `mjml -w source.mjml -o development.html` to automatically recompile on source file change.

## Exporting
  1. Run ` mjml source.mjml -o production.html`
  1. move all local assets to cloud storage (tbd) and update links in `source.mjml`
  1. Replace the main image src attribute wiht `*|IMAGEURL|*`

## Publishing
  1. Log into Mandrill through mailchimp
  1. Click on Outbound, then the Templates tab to get to the templates section
  1. Click "Create a Template"
  1. Name the template `YYMMDD[activation_name]`
  1. Click next or whatever
  1. Make sure the editing box on the right is set to HTML, then paste in the contents of `export.html`
  1. Preview with the "Preview and Test" button, then publish
  1. Have a beer and enjoy yo self
