# Knowledge Graph for Scientific Research Papers

## [View Presentation Video](https://ucsd.zoom.us/rec/share/LDUzACCs92mC3jo6EM9rUU08-GXabzkBePfu63Hlge-ZG-PAb5f46n8w7gQs6iVj.1Im_Wvs7eGbs2DWn)

## Group Members:
- Lila Horwitz
- Ashley Ho
- Mizuho Fukuda

## Instructions

1. Create SQL tables using the [schema](schema/sql_schema.txt)
1. Populate above tables using [papers.csv](data/papers.csv) for the papers table, [author_paper.csv](data/author_paper.csv) for the authors table, and [abstracts.csv](data/abstracts.csv.zip) for the abstracts table.
1. Create nodes and edges in Neo4j:
	- add the following files to the import directory: 
		- [papers.csv](data/papers.csv)
		- [authors.csv](data/authors.csv)
		- [author_paper.csv](data/author_paper.csv)
		- [references.csv](data/references.csv)
		- [venues.csv](data/venues.csv)
		- [venue_paper.csv](data/venue_paper.csv)
	- run the [cypher code](schema/neo4j_schema.txt)
1. Run the queries in the notebook [knowledge_graph_queries.ipynb](knowledge_graph_queries.ipynb)