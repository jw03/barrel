# Getting Started With Barrel

## Prerequisites
You'll need a few things to be operational and fully work with our team:

 * We deliver fully-annotated designs for development with [Sketch](https://www.sketchapp.com/). At minimum, you'll need a Mac to view these files. 
 * Supporting design files, including webfonts, often come in other formats such as those from the Adobe Creative Suite or as a public [InvisionApp](https://www.invisionapp.com/) share link. 
 * Hourly/retainer work must be tracked with [HarvestApp](http://barrel.harvestapp.com). Request an account with us.
 * We require high visibility into the development process. Code must be reviewed regularly on [Gitlab](https://www.gitlab.com). Create an account and join our group and/or project.
 * For many of our projects, functional specifications are drawn up in [JIRA](https://barrel.atlassian.net) where executional directives, bug reports, preparation tasks, and questions may be found and/or issued.
 * Review our living [best practices](https://github.com/barrel/barrel-dev-best-practices) documentation. Submit an issue or a merge request, if you have anything to contribute.


## The Test
Our projects work best when process is followed and communications are clear. We've created a few simple tasks to "test" your ability to follow directives, ask questions, and learn process.

### Objectives

1. Become familiar with the code contribution and review processes.
2. Become acquainted with development and deployment workflows for Pantheon, WP Engine, Acquia, and/or Shopify.
3. Offer feedback on how to improve the resources for the above.

### Tasks
#### Getting Setup with Pantheon
1. Sign-up for a free [Pantheon](https://pantheon.io/register) developer account.
2. Review our [process](https://docs.google.com/a/barrelny.com/document/d/1vCPXQHWXANfGFFwDDrywR3388sdxA73-WzYp8MDGO7s/edit?usp=sharing) document on working with Pantheon.
3. Import our [base theme](https://gitlab.com/barrel/barrel-base-theme) onto your site's git repo. 
4. Mirror your site on [GitLab](https://www.gitlab.com). Note that the [CI](https://about.gitlab.com/features/gitlab-ci-cd/) should be enabled. 

#### Creating a Feature
1. Create a new feature as described [here]().
2. Issue a merge request to your own gitlab repository, but do not merge it. 
3. Push your feature to a multidev environment (not dev, test, or live).
4. Assign a reviewer (whoever invited you to view this document) to the merge request, and indicate the multidev environment where the feature can be confirmed.
5. After receiving approval to move forward, accept the merge request, prepare the release, and push to dev.

#### Creating a Hotfix
1. Create a hotfix for the issue as described [here]().
2. Issue a merge request to your own gitlab repository, but do not merge it. 
3. Push your hotfix to a multidev environment (not dev, test, or live).
4. Assign a reviewer (whoever invited you to view this document) to the merge request, and indicate the multidev environment where the fix can be confirmed.
5. After receiving approval to move forward, prepare the hotfix, publish the hotfix, change the target branch of the merge request to the published hotfix, accept the merge request, delete the source branch, complete the hotfix, and push to dev.