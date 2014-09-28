Email Blueprints
================

This is the holy grail of rock solid email templates from Mailchimp, Zurb's Ink and Antwort. For previews and easy html access, see [http://cjmosure.github.io/email-blueprints/](http://cjmosure.github.io/email-blueprints/). Cheers.



[Brought to you by MailChimp](http://www.mailchimp.com/), these email blueprints are licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/). See MailChimp's [HTML Email Reference](http://templates.mailchimp.com) for their best practice guides.


Resources
---------





Contents
--------

**/modular-template-patterns** contains a single template built out of modular blocks of common design patterns.

**/responsive-templates** contains a collection of responsive / mobile-friendly email templates with various layouts.

**/templates** contains a collection of fixed-width email templates with various layouts.



Responsive Templates & CSS Inlining
-----------------------------------

When inlining the CSS in the responsive templates, be sure **not** to include the styles within the media query; they should remain in the head element of the email. The MailChimp app and [external CSS inliner](http://beaker.mailchimp.com/inline-css) both inline the CSS correctly, but many services may not.