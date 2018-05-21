---
name: Azure Logic Apps
x-slug: azure-logic-apps
description: You can connect apps, data, and devices anywhere&mdash;on-premises or
  in the cloud&mdash;with our large ecosystem of software as a service (SaaS) and
  cloud-based connectors that includes Salesforce, Office 365, Twitter, Dropbox, Google
  services, and more. Its never been easier to access data and keep your disparate
  systems up-to-date, in real-time. New connectors are being added to the Azure Marketplace
  all of the time.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
x-kinRank: "10"
x-alexaRank: ""
tags: Actions
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/actions/master/_listings/azure-logic-apps/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Logic Apps API Workflow Run Actions List
  x-api-slug: azure-logic-apps-api
  description: Gets a list of workflow run actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
  humanURL: https://azure.microsoft.com/en-us/services/logic-apps/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Logic/workflows/{workflowName}/runs/{runName}/actions
  tags: Workflow Run Actions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/actions/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftlogicworkflowsworkflownamerunsrunnameactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/actions/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftlogicworkflowsworkflownamerunsrunnameactions-get-openapi.md
- name: Azure Logic Apps API Workflow Run Actions Get
  x-api-slug: azure-logic-apps-api
  description: Gets a workflow run action.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
  humanURL: https://azure.microsoft.com/en-us/services/logic-apps/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Logic/workflows/{workflowName}/runs/{runName}/actions/{actionName}
  tags: Workflow Run Actions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/actions/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftlogicworkflowsworkflownamerunsrunnameactionsactionname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/actions/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftlogicworkflowsworkflownamerunsrunnameactionsactionname-get-openapi.md
- name: Azure Logic Apps API
  x-api-slug: azure-logic-apps-api
  description: You can connect apps, data, and devices anywhere&mdash;on-premises
    or in the cloud&mdash;with our large ecosystem of software as a service (SaaS)
    and cloud-based connectors that includes Salesforce, Office 365, Twitter, Dropbox,
    Google services, and more. Its never been easier to access data and keep your
    disparate systems up-to-date, in real-time. New connectors are being added to
    the Azure Marketplace all of the time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
  humanURL: https://azure.microsoft.com/en-us/services/logic-apps/
  baseURL: ://management.azure.com//
  tags: Actions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/actions/master/_listings/azure-logic-apps/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/logic-apps/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/logic-apps/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/logic-apps/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/logic-apps/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---