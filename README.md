 
## About Data Engineering?
Data engineering is part of the big data ecosystem and is closely linked to data science.
Data engineers work in the background and do not get the same level of attention as data
scientists, but they are critical to the process of data science. The roles and responsibilities
of a data engineer vary depending on an organization's level of data maturity and staffing
levels; however, there are some tasks, such as the extracting, loading, and transforming of
data, that are foundational to the role of a data engineer.

At the lowest level, data engineering involves the movement of data from one system or
format to another system or format. Using more common terms, data engineers query
data from a source (extract), they perform some modifications to the data (transform),
and then they put that data in a location where users can access it and know that it is
production quality (load). The terms extract, transform, and load will be used a lot
throughout this book and will often be abbreviated to ETL. This definition of data
engineering is broad and simplistic. With the help of an example, let's dig deeper into
what data engineers do.

An online retailer has a website where you can purchase widgets in a variety of colors. The
website is backed by a relational database. Every transaction is stored in the database. How
many blue widgets did the retailer sell in the last quarter?
To answer this question, you could run a SQL query on the database. This doesn't rise
to the level of needing a data engineer. But as the site grows, running queries on the
production database is no longer practical. Furthermore, there may be more than one
database that records transactions. There may be a database at different geographical
locations – for example, the retailers in North America may have a different database than
the retailers in Asia, Africa, and Europe.
Now you have entered the realm of data engineering. To answer the preceding question,
a data engineer would create connections to all of the transactional databases for each
region, extract the data, and load it into a data warehouse. From there, you could now
count the number of all the blue widgets sold.

## Table of contents
* [Building Our Data Engineering Infrastructure](#Building-Our-Data-Engineering-Infrastructure)
* [Introduction to dlt](#Introduction-to-dlt)
* [Features](#Features)
* [Building data pipeline with dlt](#Building-data-pipeline-with-dlt)
* [First pipeline](#First-pipeline)
