---
layout: page
title: Marketplace on the Cognitive Cloud
permalink: /marketplace/
hidenInHeader: true
---

<div class="screenshot"><img alt="" src="/static/files/marketplace/marketplacec_screenshot.png"></div>
<br>

#### Functionality
The Marketplace and Operational Services will ensure the availability of a data brokerage system in the form of a data marketplace where data and datasets that are part of the business graph can be provisioned and accessed. The focus here will be on the implementation of a mechanism for controlled access to business graph data, together with services for user management and data access mechanisms. In addition, the operational services needed for the marketplace will be addressed. Components for platform monitoring, availability, administration quota enforcement, branding and billing will be created. The underlying infrastructure of the marketplace will be based on the Cognitive Cloud and DataGraft.

#### Usage in euBusinessGraph
The Marketplace will implement the following scenarios:

* *Scenario 1.* A data producer has data for sale. She will export the data from her relational database system that keeps the data and will transform and interlink to the Marketplace schema with DataGraft. Then she will upload the data tshe wants to share with data consumers to the master GraphDB database. The rest of the data will be uploaded to a private GraphDB Cloud instance that she will provision via the Cognitive Cloud. The Data provider will pay for the GraphDB Cloud instance and the possibility to provide her data for sale via the master database.
* *Scenario 2.* A data producer has data for sale, but there are business or regulatory limitations to share all of the data in a provisioned instance of GraphDB Cloud. She then will export the data she wants to share with the data consumer and will link and transform it to the master schema. She will then configure a virtual database on the Marketplace that will link her internal relational database with the search component. The Data provider will pay for the virtual database and the possibility to provide her data for sale via the master database. 
* *Scenario 3.* A data consumer needs organisational data about companies from particular sector in a London district. She will use the faceted search user interface to filter organisations by location and sector. There will be data about such companies from two providers. She will explore the available data by each provider and will choose to buy the data from the one of the providers. Since the data consumer is using a subscription she will not pay for the data immediately. The billing component will charge her credit card beginning of the month and will issue and invoice for the payment.

#### Installation guide
To be developed.

#### User guide
To be developed.

#### API documentation
To be developed.

#### Software license
To be decided.

#### Source code repository
To be decided.

#### Contact person
milena.yankova [at] ontotext [dot] com
