# DA162: Share Data Products with Zero Copies using SAP Business Data Cloud Connect

Discover how to share data products across the SAP Business Data Cloud solution and third-party platforms with zero-copy access. In this session, you will learn about SAP Business Data Cloud (SAP BDC) and how the BDC Connect capability enables secure, bidirectional sharing of semantically rich data products with external platforms (here: Snowflake) without duplicating or moving data. You will see how zero-copy sharing preserves business context, governance, and metadata across environments, and walk through the end-to-end flow: from discovering data products in the BDC Catalog, to sharing them with a connected partner system via Delta Sharing, to consuming them directly in the target platform. Whether you are a data architect, analytics lead, or IT decision-maker, this session will show you how to break down data silos while keeping your trusted SAP data in place.


## Use case Description
S/4HANA sales data products are shared from SAP BDC to Snowflake via BDC Connect, enriched using Snowflake's ML.CLASSIFICATION to dynamically segment customers into spend tiers, and published back to the BDC Catalog as a governed, enriched data product ready for downstream consumption in SAP Datasphere. Walk through the end-to-end flow — from zero-copy sharing and ML enrichment to semantic view creation — and see how business users can answer questions like "Which high-value accounts are we at risk of losing?" directly from trusted, context-rich SAP data.

<br>![Use Case](/exercises/ex0/images/useCase.png)




The exercises are as follows:
- [Getting Started](exercises/ex0/)
- [Exercise 1 - Provision SAP BDC Connect and include Enterprise Snowflake in a SAP BDC Formation](exercises/ex1/README.md)
- [Exercise 2 - Share SAP-managed Data products from SAP BDC Catalog to Snowflake Horizon Catalog using SAP BDC Connect](exercises/ex2/README.md)
- [Exercise 3 - Consume SAP-managed Data product in Enterprise Snowflake (using CoCo Agent)](exercises/ex3/README.md)
- [Exercise 4 - Create and publish custom derived data product in Enterprise Snowflake](exercises/ex4/README.md)
- [Exercise 5 - Install custom data product in SAP Datasphere](exercises/ex5/README.md)
- [Exercise 6 - Catalog Governance Demo](exercises/ex6/README.md)
