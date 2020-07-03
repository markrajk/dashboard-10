# Frontend for dashboard v01
## Changes:
- Removed script from single user HEAD! feedback page and icons change
    * ```<script src="https://kit.fontawesome.com/e9f50f9a1c.js" crossorigin="anonymous"></script>```
    * ```<i class="fas fa-star"></i>``` changed to ```<i class="icon-star"></i>```
- Javascript in this version:
    * In public/js/main.js is small javascript code for opening and closing sidenav menu, as well code to automaticly close or open menu depwnding on viewport width.
    * In teams-average-charts & single-user pages there is similar javascript code at bottom in script tag:
        * teams-average-charts - on load event progress bar fill animation, numberOfChartBars is function that calculates number of charts for graph on resize it also should fire oon open/close menu.
        * In single-user same scripts as above but also script for graph slider/carousel on smaller viewports.
- Html comented code removed
- CSS code cleaned. Unececery code removed
***
## Changes 08.04.2020
- Pages added:
    * company-members, company-teams, company-admin
    * user-settings-general, user-setting-teams, user-settings-advanced
    * not everything properly linked to each other
- Modals added:
    * on index & average-charts page (should be added to other pages with same functionality):
        * follow new team modal - on follow a new team btn
        * new invitation modal - on get the mobile app TEMPORARY
        * create new team modal - on plus-circle icon, there is also second modal that is part 2 of create team dialog (its in html)
    * on teams-settings-general page:
        * link team to company modal - on last row link btn
    * on teams-settings-feedback page:
        * request feedback modal - on add new btn
    * on teams-settings-rights page:
        * new viewing rights modal - on upper add rights btn
        * new admin rights modal - on lower add rights btn
    * on teams-members page:
        * invite new members modal - on invite new member btn
    * on company-members company-teams company-admin pages:
        * register new company modal - on register a new company btn

### NOTES:
Sidenav menu is different on company pages, 1 more icon added in sidebar for company pages!
### TO DO! 
Link second create new team modal or integrate in first. FIND SOLUTION!
Link all pages and make modals work on all pages with that functionality.
 
***
## Changes 09.04.2020
- On teams-average-charts & single-user pages small month text bellow bars changed in HTML to be capitalized instead of uppercase.
- Added example function for create new team modals, changing content of first modal with second on confirm btn click, in html script tag.
    * Second step modal for create team is stil in html commented.
- All pages connected, company icon in sidebar added to all pages.
- General modals added on all pages, for presentational purposes.
- Sign in page revorked.
- Get started page added.
***
## Changes 10.04.2020
- company-settings page added.
- single-user-feedback-given page added.
- user-settings pages now with proper header, html changed.
- user-settings-teams .subheader-text & .subheader-text-small changed in html.
- top right header dropdown link text changed on all pages.
- company-admin subheader content changed in html.
- general modals now working on give-feedback page (presentational purposes).
- team-settings-rights tables changed in html.

- content of dropdowns changed on all pages.
    * average-charts months ▼
    * teams-comments latest ▼
    * teams-members ... (symbol, and in all tables where it is present)
    * teams-settings-feedback select options changed.
- CSS changes & bug fixes.
## Changes 23.06.2020
- HTML changes:
    * team-settings-general & user-settings-general input fields added & from (p class="column-01") class text-truncate removed
    * team-settings-feedback & team-settings-rights new tables (HTML changed)
    * To every dropdown-custom-trigger element HTML attribute tabindex="0" added (safari bug fix)
    * teams-average-charts & people-average-charts chart settings changed(fontSize changed & fontStyle added)
    * teams-settings-general & user-settings-general input fields & save buttons
    * people-feedback-received & people-feedback-given truncate text function changed(in script tag)
- CSS changes:
    * ./public/css/pretty-checkbox.css file updated
    * Many changes in CSS file, most of trello bugs fixed
    * Logout link now can be button tag
## Changes 24.06.2020
- HTML changes:
    * Checkboxes in report-team & report-member changed
    * people-feedback-given html of comments updated so its up to date with people-feedback-received
- CSS changes:
    * CSS file changed
- JS
    * people-feedback-received & people-feedback-given javascript function changed (in script tag)
## Changes 25.06.2020
- HTML changes:
    * teams-settings-feedback page table-section-end class removed from table rows table-section-start remains for purpopse of dividing table in sections (has some special style) 
    * teams-settings-rights table code changed (again)
    * teams-comments HTML for comments changed (as well as js function, just note, treat them as different type of comments from other ones with stars)
    * give-feedback page have example of empty notification menu (div class="dropdown-custom-list-body-none) and badge with numeber of notifications (span class="notification-menu-badge")
- CSS changes:
    * CSS file changed
    * Now clicking inside menu shouldn't close it
- JS
    * teams-comments function changed (in script tag)
## Changes 27.06.2020
- HTML changes:
    * teams-settings-general html changed, more rows and 2 modals added.
    * teams-comments, people-feedback-received & people-feedback-given placeholder element (no-feedback, class) added.
    * give-feedback page top right user menu enitials element added (user-initials) in dropdown-custom-trigger element.
        - On button tag dropdown trigger, same page, i added onclick="this.focus()", wich solves safari dropdown bug, with button element.
  
- CSS changes:
    * CSS file changed
## Changes 30.06.2020
- HTML changes:
  * company-teams, company-members & company-admin tables changed, few changes during day not sure what version you have.
  * company-settings, company description input added, as well as 2 modals for address and contact person
  * teams-settings-lead added as well as button for same page on other teams settings pages.
- CSS changes:
    * CSS file changed
## Changes 01.07.2020
- HTML changes:
  * company pages header bottom page links "Rights" changed to "Admin rights"
- CSS changes:
    * CSS file changed
## Changes 02.07.2020
- HTML changes:
  * teams-compare page added
  * company-register page added
  * In give feedback page in side menu links (Team marketing etc.) changed to buttons and i.icon-close added
- CSS changes:
    * CSS file changed
## Changes 03.07.2020
- HTML changes:
  * company-teams & company-members no entries placeholder added.
  * teams-settings-general modal added (row with modal link is commented) there is only, linked version of row, visible.
- CSS changes:
    * CSS file changed


