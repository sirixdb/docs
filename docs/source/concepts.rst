Concepts
========

SirixDB is an evolutionary, (bi-)temporal, append-only database system.

The system stores databases (as in relational DBSs) and, therein, so-called resources. Resources are the equivalent of tables in a relational DBS.
They store the actual data, currently either JSON or XML. The type of data stored is the same throughout a database. Thus, either all resources store JSON or XML data inside a database.
SirixDB currently allows importing JSON or XML documents. They are stored in resources during the import and shredded to a tree representation.
