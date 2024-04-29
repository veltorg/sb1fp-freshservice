# Freshservice styling 

- [Freshservice styling](#freshservice-styling)
  - [Why this repository](#why-this-repository)
  - [Rebranding - adjust your portal](#rebranding---adjust-your-portal)
      - [styling theme (design guide)](#styling-theme-design-guide)
      - [Previewing](#previewing)
      - [Reverting](#reverting)
    - [Custom styling](#custom-styling)
    - [Page layout](#page-layout)
    - [Translations (guide)](#translations-guide)

## Why this repository

the freshservice platform ([forretningspartner tveit freshservice][tveit-freshservice] 
is a user interface where people can submit new tickets. 
This is a customisable site. You can read more about [getting started with fresh themes here][fresh-themes].

This repository exists as a way to document and keep a version control of 
the changes we do on this support page. These files do not get automatically 
pushed to freshservice, but must be edited in the rebranding page on freshservice.

## Rebranding - [adjust your portal][portal]

#### styling theme ([design guide][design-guide])

The theme design are inspired by and follow the guidelines documented in the  [design guide][design-guide].

#### Previewing

When you work in the portal, you will be able to save your changes, and hit `Preview`.
Doing this will allow you to see your saved changes. Clicking `Publish` will commit the
change and apply it to the site. 


#### Reverting

If a change is unwanted, you can revert your changes before publishing them. you can revert
either a single page or all pages. This repository will have a history where you can find earlier
versions to add to the templates.  


**Important!**

When previewing, make sure to check that the logo, page name, and base page layout is correct. 
We have experienced a few times mid-design that the page has reverted changes such as logo or it shows default cards, which is unintentional.
Publishing those changes makes it difficult to revert through versions. 

### Custom styling

This contains css where you can set things like global styling or variables 
for the support desk. Setting a background color or font color will change appropriately.

### Page layout

The rebranding desk will have segments such as "search" or "cases". If you want to do more 
changes on a specific page, you can find the relevant page and edit the html markup and preview it.

When you are happy with the change, it is recommended to update this repository with the change,
this way it is possible to revert more consistently and document the changes.

### Translations ([guide][translations])

Freshservice offers translations. Using this, it is possible to create custom fields
that can be translated to the supported languages. 

[tveit-freshservice]: <https://forretningspartnertveit.freshservice.com/support/home>
[fresh-themes]: <https://support.freshservice.com/en/support/solutions/articles/50000003061-adding-custom-styles-to-your-portal>
[portal]: <https://forretningspartnertveit.freshservice.com/a/portals/54000001562/customise/home-page-designer>
[translations]: <https://support.freshservice.com/en/support/solutions/articles/50000000046-configure-multilingual-ticket-forms>
[design-guide]: <https://design.sparebank1.no/>