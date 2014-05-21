#### FillPDF module
This fork [FillPDF](https://drupal.org/project/fillpdf) module from [drupal.org](https://drupal.org)

#### Changes
In this fork added support the any entities.

#### Reasons
* Module has been wrote in drupal 6 style. 
* No support the entities.
* Supporting only nodes and webform submissions.

#### Installation and configuration
You can install and configuring as original fillpdf module.

#### How to use
* Callback:
_/fillpdf?fid=2&entity_type=node&entity_id=10_

* Function fillpdf_pdf_link:
```php
fillpdf_pdf_link(2, 'node',  10)
```

#### Versions and branches
Currently forked only version 1.x.
Code is available in "master" and "v1" branches.
Work on the second version of the process.
