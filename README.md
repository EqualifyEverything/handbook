# The Equalify Handbook

## What does "equalify" mean?
To "equalify" something is to fix it with an accessibility-first mindset. Accessibility-first means raising the bar of work to guarantee that people with disabilities can easily use tools and access content.

## What is the purpose of a handbook?
Equalify's handbook is modeled after [Gitlab's handbook](https://about.gitlab.com/handbook/) and contains comprehensive information about everything related to Equalify. By publishing our handbook publicly, we're fostering a culture of transparency and openness and ultimately contributing to a more accessible internet for all.

## What is Equalify?
Equalify is a platform for managing website accessibility focused on improving conformance to the Web Content Accessibility Guidelines (WCAG). We offer a managed service at https://equalify.app/ and repositories in the [EqualifyApp organization](https://github.com/EqualifyApp/) on GitHub for users to create their version of Equalify. Users who create their version are encouraged to contribute to our open-source codebase to work together to make the web more accessible to everyone.

## What is Equalify's mission?
**We aim to equalify 100 million accessibility issues by 2028.** With over 96% of the million most popular homepages failing WCAG compliance testing[^1], we have a lot of work in front of us!

## What are Equalify's core values?
Equalify is built around the belief that everyone should have access to internet tools and information. Our commitment to Open Source. All Equalify code is published under [approved Open Source licenses](https://opensource.org/licenses). Open Source licenses ensure that our software remains free and open for everyone to use, study, and modify. By making our code publicly available, we hope to inspire others to join us in equalifying the internet. 

## How is Equalify maintained?
Equalify is maintained by a team from the University of Chicago Illinois (UIC) Technology Solutions. More information can be found on the [UIC IT Accessibility Engineering page](https://it.uic.edu/accessibility/engineering/).

## How does Equalify handle project management?
- **Issue Reported in One Repo:** All issues are in the main Equalify repo at this URL: http://github.com/equalifyEverything/equalify
- **One-Week Sprint Cycles**: Each issue should contain work that fits into two-weeks. Equalify [milestones](https://github.com/EqualifyEverything/equalify/milestones) align with each sprint cycle.
- **[@bbertucc](https://github.com/bbertucc) is Project Manager**: Tag `bbertucc` with any questions that need management.

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

## How is contributor access controlled?
Contributor is controlled by [@bbertucc](http://github.com/bbertucc). As Equalify grows, the goal is to move toward a shared, community-led decision-making process.

## Will this handbook evolve?
Yes! Many changes have happened since Equalify was launched. Good tech evolves!

## How do I get in touch with Equalify?
Post additional questions, bugs, and enhancement requests under the [main repo's "Issues" tab (linked)](https://github.com/EqualifyApp/equalify/issues). Your feedback makes Equalify a better organization. We also use Slack for folks building Equalify.

[^1]: https://webaim.org/projects/million/
