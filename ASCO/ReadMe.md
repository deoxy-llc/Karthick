Project objective: Scrape data of 500+ companies from a conference database and scrape emails from company websites.

Conference website to scrape for basic information (no emails):
https://events.jspargo.com/asco19/public/Exhibitors.aspx?Index=All

Emails will need to scraped from individual company websites. Typically, three types of emails could be found: info@COMPANY.com, contact@COMPANY.com, and sales@COMPANY.com (although not all three may exist for the same company). Email is sometimes listed on a company's homepage, but more often, on the "contact" or "about us" page. 

For emails and phone numbers, you will have to write a separate script to crawl company websites. First scrape "homepage" or landing page for emails and phone numbers. If not found, then try "Contact" "About this" pages. There are typically three kinds of emails: info, sales, and contact. You can probably try identifying the following strings: "info@", "contact@", "sales@".

Example output: https://docs.google.com/spreadsheets/d/13hoyxjgNngOB3sFSv7anYLKlcCLEnuvnrV6CPTr6tdo/edit#gid=0

Some notes (when scraping the conference database):
1. Cancer type is available for only some companies. When it is absent, leave the field blank. 
2. For non-USA companies, do not need to put "State". 
