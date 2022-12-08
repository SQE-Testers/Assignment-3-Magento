# REVIEW PROCESS
They will review your extension code and submit information according to the
queue, sending feedback and confirmation by email. Track the status and
progress of your extension submission through your Marketplace account.
Their Extension Quality Program (EQP) verifies that all Marketplace extensions
meet Magento quality standards and best practices.
Before submitting your extension for review, complete the information about
the extension through the developer portal.
The extension submission process requires you to do the following:

● Review and agree to the Terms and Conditions of Commerce
Marketplace.

● Pass both technical and marketing review.

● Provide information about your business to ensure that transactions
and payments are processed efficiently. This information includes W-8 /
W-9 forms, as required by law. For more information, see the technical
and marketing review guidelines.

You can submit your extension for technical review when you are ready to
have Commerce Marketplace review the code and technical aspects of your
extension. These steps require additional information for your extension
including a PDF guide, supported Magento versions, and code package.
You can submit your extension for marketing review as soon as your
marketing content is ready for review.
You must complete both the technical and marketing review to fully list your
extension on the Commerce Marketplace.

https://devdocs.magento.com/marketplace/sellers/submit-for-review.html


### Submit for Technical Review

All extensions submitted to Commerce Marketplace must pass the automated
technical review as part of the extension submission workflow. Technical
review helps to improve the quality of products on Commerce Marketplace by
checking for indications of plagiarism, malware, and adherence to Magento
coding standards. Developers whose extensions do not pass technical review
receive a report of the results. After the issues are resolved, you are welcome
to resubmit the extension. Extensions must pass technical review to receive a
listing on Commerce Marketplace.

https://devdocs.magento.com/marketplace/sellers/submit-for-technical-review.html


When your extension entry is complete, you can submit your extension for
technical review. During the process, we review the code according to
technical guidelines, install and use the extension according to your
documentation, and verify specifics from your submission form. You can track
the status and progress of your extension submission through your
Marketplace account.

### Prepare for Technical Review
Before submitting an extension or theme for marketing review, conduct your
own internal review of the content to make sure that it is ready for publication.


● Review the technical guidelines to ensure that your extension meets
Commerce Marketplace and Magento development requirements.

● For theme extensions, verify all image, css, and code assets correctly
load on the storefront. For feature / service extensions, make sure data
and options follow coding standards, logging, etc.

● All extensions must be secure, without viruses, malware, or
vulnerabilities.

● Fully test your extension, including installation, dependencies, shared
packages, configuration, and usage.

# Submit for Marketing Review
When you have completed the code, you can submit your extension for marketing review. You can submit your product for both technical and marketing review at the same time. The review process is the same for both extensions and themes.

Your extension is placed in a queue as soon as it is submitted. You will receive confirmation by email, and can track the status of your submission from your Marketplace account.

# prepare for marketing review
Before submitting an extension or theme for marketing review, conduct your own internal review of the content to make sure that it is ready for publication.

Review the marketing guidelines to ensure that your extension meets Commerce Marketplace and Magento development requirements.
Spell-check and review all text fields in your extension, product documentation, and marketing materials.
Read the text out loud to make sure that the tone is conversational, and with no missing or transposed words.
Get a second opinion. Ask a friend or colleague to review the profile, screenshots, and any supplemental documentation.
Consider the following: Is the presentation professional? Does it foster confidence in your skills as a developer? Does it have commercial appeal? Do you provide information to help customers understand your product and how it supports their storefronts and backend?
# Submit for review
Log into the Marketplace Developer Portal, and then click Extensions.

Click the extension name you want to submit.

The Technical Submission page loads.

Click one of the entries under Marketing Submission to add marketing content.

As you complete sections, a checkmark displays tracking progress. If you updated or submitted content for the Technical Submission, the list displays checkmarks for that submitted content.

https://devdocs.magento.com/marketplace/sellers/submit-for-marketing-review.html

Marketing Submission Progress

Complete each section and submit for review when it is complete.

Click Save Submit to save progress.
Click Preview to see the output of your marketing information.
After adding all content, with full checkmarks across sections, click Submit

You will receive email confirmation when the extension is submitted for
Technical Review, and will be notified when the review is complete.



# Open source contribution requirements for developers

If you would like to contribute improvements or bug fixes to Magento, and make sure it is valuable for the Community and Magento as well, they highly recommend that Community Contributors take issues from the backlog based on Priority. 

https://devdocs.magento.com/contributor-guide/contributing.html#priority-and-severity-descriptions

Priority
The Magento team defines priorities during regular triage review meetings, based on the community assessment for severity.
Severity
Community Maintainers are allowed to set Severity labels during the initial issue triage according to the Issue Processing Workflow. And they can also set or edit severity and priority based on their internal triage process .
Issue reporters can provide their own evaluation for severity by selecting a checkbox in the Issue description.

### Pull request risk assessment
The ‘Risk:’ label highlights the risk that the suggested changes may bring to the platform. It helps maintainers decide:
to which version the pull requests should be delivered
which reviewers should see it

whether a request should be approved or not


### RISK DESCRIPTION
#### High
A pull request that makes changes on the framework or changes that will affect multiple areas.
#### Medium
A pull request that makes changes which may affect multiple areas or makes considerable changes on a specific area.
### low 
A pull request that will probably not affect other areas.

You can also use two factor authentication.

they capture code-related issues in the Magento 2 repo and documentation-related issues in the DevDocs repository

https://devdocs.magento.com/contributor-guide/contributing.html#question

### Contribution requirements

- Contributions must adhere to coding standards.
- A pull request (PR) should be accompanied by a meaningful description of its purpose.
-  A detailed description makes it more likely that the pull request will be merged quickly without requiring further clarification. A commit should be accompanied by a meaningful commit message.
- PRs containing bug fixes must be accompanied by step-by-step instructions on how to reproduce the bug.
- PRs containing new logic or new functionality must be submitted with:
 
- Unit/integration test coverage.

https://devdocs.magento.com/contributor-guide/contributing.html#requirements

### forks and pull request

Choose an issue to work on and assign it yourself
- fork the repository
- create a branch
- fix/implement functionality
- Cover changes with tests
- open pull request
- Start your tests and make sure they are green.
 
https://devdocs.magento.com/contributor-guide/contributing.html#forks-and-pull-requests

### Commits
In some cases, a pull request may contain multiple commits (main commit, subsequent post-review changes, etc.). A good practice is to ship commits with feature parts/bugfixes ready. In this case, all intermediate commits such as static test fixes, typo fixes, minor refactorings, etc. should be merged into one commit. This keeps a clean history and makes the repo easier to read.
https://devdocs.magento.com/contributor-guide/contributing.html#squash-commits

### Assigning an issue

Command: To assign as issue to your GitHub account, add the following command as a comment to the issue:
@magento I am working on this



This command has several variations:
- @magento I am working on this
- @magento I am working on it
- @magento I'm working on this
- @magento I'm working on it

The following actions will occur 

- if the user is member of magneto github organization ticket will assigned to it else an invitation will send to its email. After accepting the invitation ticket will assigned to it.

https://devdocs.magento.com/contributor-guide/contributing.html#assigning-an-issue

If you want to check an issue or pull request, use the instance command to generate a Magento instance. This is a clean install of a branch with a specific version tag or a specific version line.
Instructions:
To provision a Magento instance, add the following command as a comment to your GitHub pull request or issue.

Give me @magento instance {$version}



Replace {$version} with your version tag or branch. The following values ​​are supported:
Version tag for the latest version and 2.4-develop for the development branch.

### Import source code to specific repository
The import command provides the ability to copy a contributor’s code or pull request into an internal fork. The internal team can then proceed with additional fixes or delivery.
Command: To import code or a pull request, a member of the Magento team controlling the pull request enters the following command:
@magento import {code|pr} to {organizationName}/{repositoryName}



Usage Examples:
To import the code only use
@magento import code to magento-team/magento2
@magento import code to https://github.com/magento-team/magento2



To import the pull request use
@magento import pr to magento-team/magento2
@magento import pull request to magento-team/magento2
@magento import pr to https://github.com/magento-team/magento2
@magento import pull request to https://github.com/magento-team/magento2



Actions:

- Code: A branch with a copy of the contributor’s source code is created within the target repository.
- PR: A copy of the pull request is created within the target repository.


### Report an issue
To maintain an effective bug fix workflow, we ask reporters to follow some simple guidelines.
Before creating an issue, do the following:

https://devdocs.magento.com/contributor-guide/contributing.html#report

- Check the Developer Documentation and User Guide to make sure the behavior you are reporting is really a bug, not a feature.
- Check the existing issues to make sure you are not duplicating somebody’s work.
- Ensure that information you are reporting is a technical issue. Refer to the Community Forums or Magento Stack Exchange for technical questions, feature requests, etc.
- Verify that the issue you are reporting does not relate to Adobe Commerce. GitHub is intended for Magento Open Source users to report on issues related to Open Source only. You can report Commerce-related issues one of two ways:
- Use the Support portal associated with your account
- If you are a Partner reporting on behalf of a merchant, use the Partner portal
- Check if the issue exists on the 2.4-develop branch with a clean Magento installation. they only accept pull requests for the 2.4-develop branch. If the issue is not reproducible on the 2.4-develop branch, it will be closed.
- If you are sure that the problem you are experiencing is a bug, file a new issue in GitHub following the recommendations below.
### Issue template
The Issue Reporting Template is a default placeholder for every new issue.

https://devdocs.magento.com/contributor-guide/contributing.html#issue-template

#### title
The title is a vital part of the bug report. A well written title should contain a clear, brief explanation of the issue, emphasizing the most important points.
- A good example:
“Unable to place order with Virtual product and PayPal.”
An unclear example:
“Can’t checkout.”
### Issue description
https://devdocs.magento.com/contributor-guide/contributing.html#issue-description

Preconditions

- System configuration settings you have changed
- Detailed information on entities created (Products, Customers, etc)
- Magento version
- Anything else that would help a developer reproduce the bug

### Steps to reproduce
Good steps to reproduce are vital to a good bug report. The issue is more likely to be fixed if it can be reproduced.
Try to include as much information as possible; even minor details could be crucial.
- Example:
Navigate to storefront as a guest.
Open Test Category.
Click “Add to Cart” on the Virtual Product.
Open mini shopping cart and click “Proceed to Checkout”.
### Actual and expected result
To ensure that everybody involved in the fix understands the issue, precisely describe the result you expected to get and the result you actually observed after performing the steps.
- Expected result:
Order is placed successfully, customer is redirected to the success page.
- Actual result:
“Place order” button is not visible, order cannot be placed.
### Additional information
Additional information is often requested when the bug report is processed. You can save time by providing both Magento and browser logs, screenshots, repository branch and HEAD commit you checked out to install Magento and any other artifacts related to the issue.
Once the issue is created, it must pass through a series of Magento Issue Gates.
Help triage issues 
In addition to contributing code, you can help triage issues. This can include reproducing bug reports or asking for vital information, such as affected versions or instructions to reproduce bugs. If you want to triage issues, you can begin by subscribing to Magento on CodeTriage.
Labels applied by the Community Engineering team
they apply labels to public pull requests and issues to help other participants retrieve additional information about current progress, component assignments, Magento release lines, and much more. The following information details global labels used in Magento 2 repositories and across Community Engineering contributions.
### Release Lines
Release line labels indicate the specific Magento release lines affected by the issue or PR. For example, if working on a fix for 2.4.0 you would apply the Release Line: 2.4. This effectively includes all releases in this line.
- Release Line: 2.3
- Release Line: 2.4

https://devdocs.magento.com/contributor-guide/contributing.html#requirements

### Progress
Progress labels indicate the Pull Request status on each review stage:
- Progress: needs update - The Community Engineering Team needs additional information from the reporter to properly prioritize and process the pull request.
- Progress: on hold - The pull request is on hold due and will be further reviewed to accept or reject.
- Progress: accept - The pull request has been accepted and will be merged into mainline code.
- Progress: reject - The pull request has been rejected and will not be merged into mainline code. Possible reasons can include but are not limited to: issue has already been fixed in another code contribution, or there is an issue with the code contribution.
https://devdocs.magento.com/contributor-guide/contributing.html#requirements


### Components
Component labels indicate the components affected by the Pull Request. To learn more about available components and assigned architects, see Magento Components Assignment.
Example labels:
- Component: Catalog
- Component: Report
- Component: Checkout
https://devdocs.magento.com/contributor-guide/contributing.html#requirements


### General
General labels include a variety of tasks and definitions for pull requests and issues.
- good first issue - Indicates a good issue for first-time contributors.
- help wanted - Indicates the creator or author needs help with a decision, advice for resolving, and so on.
- triage wanted - Indicates the issues are under triage. See this information to learn more about the Triage Wanted program.
https://devdocs.magento.com/contributor-guide/contributing.html#requirements

### Issue resolution status
Labels applied to issues through verification and completion. For details on the process, see GitHub Issues Processing Workflow.
- Issue: Format is not valid - Gate 1 failed. Automatic verification by the Automated Contributor Assistant failed and the issue needs updates. The format of the issue description and minimum required information is not provided: Preconditions, Steps to Reproduce, Actual Result, Expected Result. Previous label G1 Failed.
- Issue: Format is valid - Gate 1 passed. Automatic verification by the Automated Contributor Assistant passed for all issue content. Previous label G1 Passed.
- Issue: Clear Description - Gate 2 passed. The Community Engineering Team has confirmed that this issue contains the minimum required information to reproduce. Previous label G2 Passed.
- Issue: Cannot Reproduce - Gate 3 failed. The issue could not be reproduced or validated. Previous label Cannot Reproduce.
- Issue: Confirmed - Gate 3 passed. Manual verification of the issue description and reproduction steps was confirmed. Previous label G3 Passed.
- Issue: Ready for Work - Gate 4 passed. The issue is acknowledged and added to the backlog for open development. Previous label acknowledged.

https://github.com/magento/magento2/wiki/GitHub-Issues-Processing-Workflow


### DevDocs
All contributions to DevDocs receive the following labels:
- New topic- New topic submissions for content that has never existed on DevDocs such as tutorials, references, instructions, and so on
- Major update - Significant original updates to existing content
- Technical - Updates to the code or processes that alter the technical content of the document, such as code snippets, reference documentation, parameter names and values, and other relevant content
- Editorial - Fixes for typos, grammatical inconsistencies, or minor rewrites to correct inaccuracies

 https://github.com/magento/devdocs/blob/master/.github/CONTRIBUTING.md



 # Issue life cycle management
 
https://devdocs.magento.com/contributor-guide/processing-workflow.html

The GitHub issue workflow ensures that issues are clear, they'll written, and thoroughly vetted. 
- Reporter - The user who filed the initial issue report. 
-  Maintainer - A member of the Community Maintainers Team who is working on the issue report to update and confirm the report in accordance with all requirements. 
- Automated Contributor Assistant - Non-human users/bots that perform automatic checks and provide assistance to human users. 
- Label - The GitHub label applied to the ticket. Following these procedures allows valid issues to get the attention they deserve
Issues reported on the public github must go through a series of processes.
Quality assessment gates or stages to ensure quality meets requirements
Norms. There are 3 gates and the output must pass through all 3.
These ratings are not forwarded to core developers, or
Community developer. The purpose of these gates is to identify the core
View technical issues and progress common to all reported tickets
Reported issue
use the goal
An issue gate is a set of steps to ensure that an issue has everyone on board.
Information needed to reproduce the bug. This includes the system
Configurations, required configurations, replication steps, etc.
Necessary information.
- Gate 1:
Validate report format – ensure report content is well-formed
and structure meet all requirements.
- Gate 2:
manual verification - someone manually verifies all this
You have provided the required information:
Reproduction procedure, system
composition etc.
- Gate 3:
Reproduce the error - someone setup the environment and try
Reproduce the error. The issue is then confirmed or closed.
##### Gate 1 - Review Report Format
The main purpose of this first stage of verification is to confirm that the report was done as such.
Well-structured content that meets your problem reporting needs
guidelines. This phase seems trivial and formal, but it definitely makes an impact
processing speed. In general, the expected structure and
Clear information is processed faster than the same report with bad reports
format. Reported issues must contain all of the following keywords
Description section:
 
- Prerequisites
- Reproduction procedure
- Results
- Expected results
Supervisors can ask the reporter to update the problem description.
Provides additional information. The maintainer adds an issue:
needs
Updated label. Reporters are given 14 days to update their problem description.
Otherwise, the issue will be closed. Maintainers can update issues
A descriptive format when sufficient information is provided.
#### Gate 2 - Manual Review
Gate 2 verifies that the submitted issue is ready for development. until the end
Has been reviewed for development including all labels for process, function
Regions, affected versions, etc. The steps to reproduce are correct,
Issues reported are defects that need to be fixed and are not due to misuse.
setting error. Working on problem reports as a reporter, maintainer, or developer is always one.
Obligation. It is beneficial for each participant to monitor the activity
Provide comments and all necessary information on tickets that are still valid
information or knowledge.
Preparation
These are steps to verify the problem, verification of steps to reproduce, and
Hire a supervisor to do it.
- Maintainer picks an open issue from her GitHub tracker. or
The recommended tool is the Issue Confirmation and Triage Board.
- The maintainer checks the "ready to review" list
Click a column to select an issue and start editing.
- After selecting the ticket, the supervisor will confirm the explanation,
reproductive procedure. 
- When the maintainer is ready to start working on the issue,
Supervisors must assign tickets to themselves. this is
Someone is actively working on the problem.
inspection
These are the steps to validate the output format and all information
Provided checks:
 
##### When entering a question
make sure it meets all of the following requirements:
Problem report template and guidelines. If the format is not valid,
The maintainer should read the report carefully and edit the issue to improve it
Match one of the required templates. 
- The maintainer can select the issue and see all the information.
Duplication of procedures, etc. In case of incomplete information from the person in charge
Request more information from reporters and apply problem labels
:
Need to update. Suspending all work on this ticket until the reporter provides
For more information.
- If the ticket contains enough information, the maintainer analyzes the ticket.
Issue stated in the ticket:
The described steps to reproduce are valid and
The expected behavior is valid and the configuration described in the prerequisites
valid.
#### Is it verified?
- If all information provided is clear and sufficient, it will be verified.
- If not verified, the maintainer adds the label Problem:.
need to update
Request further information from the reporter. Diploma
Procedure for final review of the issue so that contributors/developers can work on the issue
output.
#### Make sure all the necessary conditions are met.
 
- The output format is valid.
- The problem is reproducible in one of the supported versions and labeled accordingly.

# VERSION AND RELEASE MANAGEMENT
The latest version of magento is 2.4.5-p1.
Before the release notes of this version they have versions
- 2.4.5
- 2.4.4-p2
-  2.4.4-p1
-  2.4.4
-  2.4.3-p3
-  2.4.3-p2
-  2.4.3-p1
-  2.4.3
-  2.4.2-p2
-  2.4.2
-  2.4.1
-  2.4.0 etc.

The p1 suffix denotes the full release for the quarterly update and contains further fixes to a unique error.

The 2.4.5-p1 version is a security release that provides five security fixes
that enhance your Adobe Commerce 2.4.5 or Magento Open Source 2.4.5
deployment. It provides fixes for vulnerabilities that have been identified in
the previous release (Adobe Commerce 2.4.5 and Magento Open Source
2.4.5).
This security patch includes five security bug fixes.
-  One fix included the creation of a new configuration setting.
-  The Require email confirmation if email has been changed
configuration setting lets administrators require email confirmation
when an admin user changes their email address
