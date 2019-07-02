---
header-id: propagation-of-changes
---

# Propagation of Changes

[TOC levels=1-4]

If you make an update to a Page Fragment or Content Page Template, it doesn't
automatically propagate changes, but you can access the *Usages and Propagation*
page to selectively propagate changes.

1.  From the Site Administration menu, go to *Site Builder* &rarr; *Page 
    Fragments*

2.  Select the Collection containing the changed fragment.

3.  Open the menu for the fragment and select *View Usages*.

The *Usages and Propagation* page shows a list of every Page, Page Template, 
and Display Page that uses the selected Page Fragment. You can then selectively
propagate fragment changes to any or all of the pages listed. You can use the
various filters and selection options to apply updates to pages quickly.

![Figure 1: Viewing the Usages and Propagation page.](../../../../../images/fragment-usages-and-propagation.png)

To update a page or template,

1.  Select the page or pages you want to update by checking the box next to the
    page name.

2.  Click the *Propagate* icon (
    ![Propagate](../../../../../images/icon-propagate.png))
    
After you propagate changes, visit any effected pages to verify there were no
unexpected side effects of the changes. Changes to existing `editable` fields 
are not propagated since this overwrites content currently in content 
pages. To force propagation to content in an `editable` field, a developer must 
change the field ID. Any content created in that field will no longer display 
in the Content Page when the changes are propagated, but it will remain in the 
database and can be retrieved using the old ID.

Next you'll learn how to import and export Page Fragments.
