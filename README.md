# TemplateTester
ProcessWire module for testing alternative PHP template files

# Status
Beta

# Description
Adds a field 'Alternative template file for testing' to the template configuration.

You can also configure which users will see the alternative template file.
You can select from:
- All logged in users
- Users with edit permissions for the individual page
  This is equivalent to a $page->editable() call for the user viewing the page.
- Users with certain roles
  If you select this, a multi select for the roles in question is opened.
  This allows you to add e.g. a 'preview' role to PW to only make the
  template file visible to select users.

All other users and guests will still see the pages rendered by the original template file.

# Warning
Caching is not taken into account.

# License
Licensed under Mozilla Public License 2.0. See file LICENSE for details.
