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

## Richie-enabled

This repo is enabled with the [markdown enricher (Richie)](https://github.ibm.com/cloud-docs-automation/md-enricher-for-cicd/wiki/Overview) which allows writers to single-source content delivery from one branch to multiple branches in the same or different GitHub repositories. It also has a number of other really cool features in the [Usage Guide](https://github.ibm.com/cloud-docs-automation/md-enricher-for-cicd/wiki/Usage)

All PR's for new content should be made against the `source` branch. When content is committed to the `source` branch, the Travis script invokes the Richie. When Richie finishes its processing, it pushes the result to the `draft` branch.

## Checking build status

Build status can be found in the [`#docs-framework-financial-services-controls`](https://ibm-cloudplatform.slack.com/archives/C03PQPM27NV) Slack channel.
