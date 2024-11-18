# The Equalify Handbook

## What does "equalify" mean?
To "equalify" something is to fix it with an accessibility-first mindset. Accessibility-first means raising the bar of work to guarantee that people with disabilities can use tools and access content with ease.

## What is the purpose of a handbook?
Equalify's handbook is modeled after [Gitlab's handbook](https://about.gitlab.com/handbook/) and contains comprehensive information about everything related to Equalify. By publishing our handbook publicly, we're fostering a culture of transparency and openness, and ultimately contributing to a more accessible internet for all.

## What is Equalify?
Equalify is a platform for managing website accessibility, focused on improving conformance to the Web Content Accessibility Guidelines (WCAG). We offer a managed service at https://equalify.app/ and repositories in the [EqualifyApp organization](https://github.com/EqualifyApp/) on GitHub for users to create their version of Equalify. Users who create their version are encouraged to contribute to our open-source codebase so that we can work together to make the web more accessible to everyone.

## What is Equalify's mission?
**We aim to equalify 100 million accessibility issues by 2028.** With over 96% of the million most popular homepages failing WCAG compliance testing[^1], we have a lot of work in front of us!

## What are Equalify's core values?
At Equalify, we believe everyone should have access to internet tools and information. Our commitment to access is reflected in both our mission (100 million equalified accessibility issues by 2028) and our business practices, typified by this handbook. Additionally, our code will be published under Open Source licenses. Open Source licenses ensure that our software remains free and open for everyone to use, study, and modify. By making our code publicly available, we hope to inspire others to join us in equalifying the internet. 

## How is Equalify sustained?
Equalify is commercialized open source software (COSS). We sustain ourselves by selling subscriptions to our managed service, https://equalify.app. We follow a skinny to thin crust open core model, more info on that [here](https://twitter.com/bbertucc/status/1693449703453589898?s=20).

## Who owns Equalify?
Blake Bertuccelli-Booth ([@bbertucc](https://github.com/bbertucc)) currently has ownership of Equalify, as noted in our [Legal Repo](https://github.com/EqualifyEverything/equalify-legal/). Blake plans to retain ownership until the organization reaches sustainability.

## How does Equalify use funds?
Our funds go to bounties. We aim to pay people bounties for getting the work of Equalify done. As of now (June 12, 2024), we've budgeted $11k/mo for bounties for the first year, then doubling that number each year after. You can see our budgets in our [Accounting Repo](https://github.com/EqualifyEverything/equalify-accounting/). In Year 5, or whenever we get to sustainability, we'll probably hire people in more traditional employment arrangements. (That will probably also be the time Blake hands over control to someone else, preferably someone who relies on assistive technology.)

## How are bounties budgeted?
Equalify has a standard rate of $70/hr. This rate was agreed on at our November 18 meeting. Every bountied issue should be estimated, approved, and invoiced at the end of the month accordingly.

## How does Equalify handle change management?
All issues are in the main Equalify repo at this URL: http://github.com/equalifyEverything/equalify 

### Development Process
Each feature has initial development, functionality testing, accessibility testing, and deployment scoped. The scope includes due date, overview of expectations, and budget.

Issue [#422](https://github.com/EqualifyEverything/equalify/issues/422) is an example of a detailed list of functionality and accessibility tests for our version one. The date that everyone agrees on is set using milestones. We check in on the progress asynchronously and every contributor meeting.

### Deploying Updates
Here is how an issue goes to production:
1. Create a GitHub Issue.
2. [@bbertucc](http://github.com/bbertucc) will assign someone to the issue.
3. Assignee creates a branch for the update.
4. Assignee merges any updates with staging branch.
5. Assignee comments on an issue that the update is ready for testing and assigns [@bbertucc](http://github.com/bbertucc) to test.
6. Update is reviewed by [@bbertucc](http://github.com/bbertucc). He may add  [@kevinandrews1](https://github.com/kevinandrews1) or [@alexstine](https://github.com/alexstine) if accessibility needs to be tested.
7. When update is finalized, [@bbertucc](http://github.com/bbertucc) creates a PR to merge with main branch and assigns [@azdak](https://github.com/azdak), [@wilsuriel03](https://github.com/wilsuriel03), [@alexstine](https://github.com/alexstine) or [@heythisischris](https://github.com/heythisischris) to review code.
8. When approved, update is merged with main branch.
9. [@bbertucc](http://github.com/bbertucc) will run final tests on production and close issue if update is finished.

*[@bbertucc](http://github.com/bbertucc) will rush any hotfixes outside of deployment process. 

## Will this handbook evolve?
Yes! Equalify Inc. was founded recently (August 7, 2023). As we meet new challenges, this document will evolve.

## How do I get in touch with Equalify?
Post additional questions, bugs, and enhancement requests under the [main repo's "Issues" tab (linked)](https://github.com/EqualifyApp/equalify/issues). Your feedback makes Equalify a better organization. We also use Slack for folks building Equalify. You can join our Slack here: https://join.slack.com/t/equalifyapp/shared_invite/zt-1sfbgf0fa-CzIHlbFOs0Ww1iSTK4LQ2w

[^1]: https://webaim.org/projects/million/
