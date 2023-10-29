# framework-financial-services-controls

Contains controls and above-the-line implementation and evidence guidance for clients/partners using the IBM Cloud for Financial Services.

# Relation to Agile Authoring System

Content in this repo is populated from [cloud-governance-framework/guidance](https://github.ibm.com/cloud-governance-framework/guidance).

## Cloud Docs locations

* [Staging](https://test.cloud.ibm.com/docs/framework-financial-services-controls
)
* [Production](https://cloud.ibm.com/docs/framework-financial-services-controls
)

## Content Design and Development in IBM Cloud

To learn about using the Cloud Docs framework, see [Content Design and Development in IBM Cloud](https://test.cloud.ibm.com/docs/writing?topic=writing-get-started-onboarding).

## Markdown Enricher-enabled

This repo is enabled with the [Markdown Enricher](https://pages.github.ibm.com/cloud-docs-automation/md-enricher-for-cicd/#/). The Markdown Enricher is a pre-processing script that brings a few of the best features of more complex authoring methods to markdown and other text-based files.

**All PR's for new content should be made against the `source` branch.** When content is committed to the `source` branch, the Travis script invokes Markdown Enricher. When Richie finishes its processing, it pushes the result to the `draft` and `review` branches (and creates a PR to the `publish` branch).

NOTE: By using the [feature flags feature ](https://pages.github.ibm.com/cloud-docs-automation/md-enricher-for-cicd/#/feature-flags) of the Markdown Enricher and the specific [feature-flags.json](https://github.ibm.com/cloud-docs/framework-financial-services-controls/blob/source/feature-flags.json) file in this repo, you can use the following tags to control which branches content is published to:

- no tag -- Content goes to all branches
- `dev` -- Content will only show up in `draft` branch
- `staging` -- Content will show up in both `draft` and `review` branches (and _not_ the `publish` branch)
- `prod` -- Content will show up only in `publish` branch (and only once `review` branch is merged to `publish` branch via the PR created by Markdown Enricher)

## Checking build status

Build status can be found in the [`#docs-framework-financial-services-controls`](https://ibm-cloudplatform.slack.com/archives/C03PQPM27NV) Slack channel.
