# Mongo DB

MongoDB is a tool to explore data structured as you see fit. As a NoSQL database, it doesn't follow the strict relational format imposed by SQL. By providing capabilities that typically require adding layers to SQL, it collapses complexity. With dynamic schema, you can handle vastly different data together and consolidate analytics. The flexibility of MongoDB empowers you to keep improving and fix issues as your requirements evolve. In this part, we will learn the MongoDB language and apply it to search and analytics. Working with unprocessed data from the official nobelprize.org API, we will explore and answer questions about Nobel Laureates and prizes.

## Flexibly Structured Data
We  will relate MongoDB documents, collections, and databases to JSON and Python types. We'll then use filters, operators, and dot notation to explore substructure.

## Working with Distinct Values and Sets
This part is about dipping your toes into the pools of values for various fields. we'll collect distinct values, test for membership in sets, and match values to patterns.

## Get Only What You Need, and Fast
We can now query collections with ease and collect documents to examine and analyze with Python. But this process is sometimes slow and onerous for large collections and documents. This part is about various ways to speed up and simplify that process

## Aggregation Pipelines: Let the Server Do It For You
We've used projection, sorting, indexing, and limits to speed up data fetching. But there are still annoying performance bottlenecks in your analysis pipelines. we still need to fetch a ton of data. Thus, network bandwidth and downstream processing and memory capacity still impact performance. This part is about using MongoDB to perform aggregations for you on the server.