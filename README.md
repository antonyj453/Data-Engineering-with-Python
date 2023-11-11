 
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
* [Required skills and knowledge to be a data engineer](#Required-skills-and-knowledge-to-be-a-data-engineer)
* [Reference](#Reference)
  
## Required skills and knowledge to be a data engineer
At the start of a data pipeline, data engineers need to know how to extract data from files
in different formats or different types of databases. This means data engineers need to
know several languages used to perform many different tasks, such as SQL and Python.
During the transformation phase of the data pipeline, data engineers need to be familiar
with data modeling and structures. They will also need to understand the business and
what knowledge and insight they are hoping to extract from the data because this will
impact the design of the data models.
The loading of data into the data warehouse means there needs to be a data warehouse
with a schema to hold the data. This is also usually the responsibility of the data engineer.
Data engineers will need to know the basics of data warehouse design, as well as the types
of databases used in their construction.
Lastly, the entire infrastructure that the data pipeline runs on could be the responsibility
of the data engineer. They need to know how to manage Linux servers, as well as how
to install and configure software such as Apache Airflow or NiFi. As organizations
move to the cloud, the data engineer now needs to be familiar with spinning up the
infrastructure on the cloud platform used by the organization – Amazon, Google Cloud
Platform, or Azure.
## Reference
[Data Enigneering with Python](https://github.com/PacktPublishing/Data-Engineering-with-Python)
