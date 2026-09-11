# SQL & Google BigQuery Practice Lab

[![SQL](https://img.shields.io/badge/SQL-BigQuery-blue.svg?logo=google-cloud&logoColor=white)](https://cloud.google.com/bigquery)
[![Kaggle](https://img.shields.io/badge/Kaggle-Certified-20beff.svg?logo=kaggle&logoColor=white)](https://www.kaggle.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![Intro to SQL Certificate](image_bd97c8.jpg)](image_bd97c8.jpg)  
[![Advanced SQL Certificate](image_bd97d1.jpg)](image_bd97d1.jpg)

Practical implementation of cloud-based relational database queries and advanced data manipulation scripts using **Google BigQuery** and the Python client library. 

This repository documents hands-on query implementations and dataset explorations completed as part of the **Kaggle Intro to SQL** and **Advanced SQL** certification programs. It demonstrates proficiency in writing optimized data aggregation, filtering, window functions, table joins, common table expressions (CTEs), and parsing nested/repeated schemas on massive public datasets.

---

## 📌 Core Topics & Datasets Explored

* **Client Connection & Schema Exploration:**
  * Initializing BigQuery client sessions and managing cloud credential authentication.
  * Inspecting table schemas (`SchemaField`), row counts, and column metadata (`Hacker News` full dataset).
* **Data Filtering & Aggregation:**
  * Writing conditional queries using `WHERE`, `GROUP BY`, and `HAVING` filters.
  * Column aliasing (`AS`) and optimizing row counting via `COUNT(1)` (`OpenAQ` global air quality).
* **Advanced Joins & Common Table Expressions (CTEs):**
  * Combining multiple tables via `INNER JOIN` and structuring multi-step queries with `WITH` clauses (`GitHub Repos` metadata, pet/owner relational models).
* **Time-Series Analysis & Date Extractions:**
  * Extracting temporal components (`EXTRACT(DAYOFWEEK)`, `DATE()`) to analyze cyclical trends in large-scale event logs (`NHTSA Traffic Fatalities`, `Bitcoin Transactions`).
* **Advanced Window Functions & Analytic Queries:**
  * Implementing cumulative totals and row-position tracking via window functions (`SUM() OVER`, `FIRST_VALUE`, `LAST_VALUE`) (`San Francisco Bikeshare`).
* **Nested & Repeated Records (JSON Schema Parsing):**
  * Unnesting complex nested arrays (`UNNEST(hits)`) to parse hierarchical Google Analytics e-commerce sessions without expensive explicit joins (`Google Analytics Sample`).

---

## 📁 Repository Structure

```text
├── 1.ipynb          # Comprehensive notebook containing client setup, public dataset queries, and analytic patterns
└── README.md        # Technical overview, documentation, and certifications
