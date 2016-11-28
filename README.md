# tenant_screening
Drupal 7 custom module. Pulls Tenant Screening Articles from AAOA RSS as a nodes.

## Install
1. Downlod the zip file from github https://github.com/vitworks/tenant_screening
2. Copy the tenat_screening folder into /sites/all/modules/custom
3. Enable the module from Modules page

Note: Requires: Feeds, Chaos tools, Job Scheduler, Feeds XPath Parser

### Get RSS feeds from AAOA
1. Go to Configuration -> Tenant Screening Advice -> Tenant Screening Advice settings
2. Copy the feeds URL
3. Click on the link to go to importer page
4. Paste the feeds URL
5. Submit.

You should have all the latests Teanant Screening articles as nodes. The status is set to "not published" so you can edit the articles that you like and publish them once you approve them.

Enjoy!
