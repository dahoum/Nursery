# Domain

## Represent w/ a Constant/ Variable/ Tag

Always represent the domain w/ a constant/ variable/ tag, which is set in a central place for the whole site in a way, which is aware of the environment (eg. production/ live, stage/ acceptance, etc.).

Do this everywhere:

* in the software
  * eg. when creating callback/ return URLs for API calls
* in the translation/ localisation string (use tags)
* in templates
  * eg. when inserting server side images in email templates

Else you may end up in a sitiation, where the production/ live site or messages it sends (emails, etc.) lead to the wrong URL.
