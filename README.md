cmsms-SubsectionHeaders
=======================

adds a secondary "section header" content type for cmsms 1.11.x series.

This module is a lightly modified mashup of the core "section header" content type and the Content Aliases module (as a lightweight example of how to create/clone a content type without hacking the core). So thanks to those devs. 

disclaimer: I suspect the upcoming cmsms 2.0 will make this module obsolete. Also, this module was mainly created as a learning exercise and to fill a need. Posting here in case it is useful and to check out git/github.

How to use: 

After installing the module, you will have a new "Section Header" content type available called "Subsection Header". First, you must import the menu or menus you are using in your template into the database via the menu manager. Then, also in menu manager, in your newly imported menu template, duplicate and subsequently alter the duplicated "sectionheader" related smarty and html by adding "sub" in front of "sectionheader". Then use it the same way you would use the "Section Header" content type and style it differently in your style sheet(assuming that's the functionality you were seeking).

