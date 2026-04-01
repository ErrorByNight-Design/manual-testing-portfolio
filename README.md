# manual-testing-portfolio
Basic test plan for Canamo+ Construction
Manual Testing Project — Canamo Plus Construction (canamoplus.com)

Project Overview
Manual test plan and bug report for a live Canadian construction company website in Montreal. This project was completed as requested by Canamo Project Manager.
What Was Tested

Navigation and internal links
Get a Quote form — field validation and boundary testing
Footer contact form — validation testing
Language toggle (FR/EN)
Social media links (LinkedIn, Instagram)
Responsiveness across desktop and mobile viewports
XSS input boundary testing

Results
25 test cases executed
19 passed, 5 failed, 1 not executed
5 defects identified and logged in Jira

Defects Found
CANAMO-001 - Quote form submits without Company Name - High
CANAMO-002 - Quote form accepts invalid email format - High
CANAMO-003 - Phone field accepts alphabetical characters - Medium
CANAMO-004 - Footer form accepts invalid email format - High
CANAMO-005 - Instagram social link leads to broken page - Medium

Tools Used
Jira — bug tracking and defect lifecycle management
Excel — test plan and test case documentation
Chrome DevTools — responsiveness and mobile testing
