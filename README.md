ETL Customer Revenue Project (Azure Data Factory)

 Project Overview

Built an end-to-end ETL pipeline using Azure Data Factory to process raw datasets and generate customer-level revenue insights.

---

Architecture

* Source: CSV files stored in Azure Blob Storage (raw layer)
* Transformation: Azure Data Factory Data Flow
* Sink: Processed CSV stored in Blob Storage (processed layer)

---

ETL Flow

1. Ingest raw datasets (customers, orders, payments, products)
2. Perform joins across datasets using Data Flow transformations
3. Create derived columns for revenue calculation
4. Aggregate revenue at customer level
5. Store final output in Blob Storage

---

 Tools & Technologies

* Azure Data Factory
* Azure Blob Storage
* Data Flow transformations (Join, Derived Column, Aggregate)

---

Output

Generated customer-level revenue dataset stored as CSV in Blob Storage.

---

Key Learnings

* Built an end-to-end ETL pipeline from scratch
* Implemented joins and aggregations using Data Flows
* Debugged and validated pipeline execution
* Published and triggered pipeline successfully

---

Future Enhancements

* Implement incremental load
* Add parameterization for dynamic pipelines
* Improve pipeline performance optimization
