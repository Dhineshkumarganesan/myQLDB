# myQLDB


https://aws.amazon.com/qldb/resources/


https://docs.aws.amazon.com/qldb/latest/developerguide/what-is.html

https://partiql.org/


https://youtu.be/BiEbMJ86dGQ

https://youtu.be/XGeCNr8eOiA

Amazon QLDB supports the PartiQL query language. PartiQL provides SQL-compatible query access across multiple data stores containing structured data, semistructured data, and nested data.


A journal is the chained set of all blocks committed in your ledger. A block is an object that is committed to the journal in a transaction. The journal represents a complete and immutable history of all the changes to your ledger data.

With Amazon QLDB, you pay only for what you use with no minimum fees or mandatory service usage. You are billed separately for write IO requests, read IO requests, journal storage, indexed storage, and data transfer


**Which of the following statements describes Amazon QLDB? (Select TWO.)**

It is a purpose-built ledger database that provides cryptographically verifiable history. (Correct)
It is a blockchain or distributed ledger technology.
It is a fully managed ledger database. (Correct)
It provides transparent but mutable transaction logs.
Amazon QLDB is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log ‎owned by a central trusted authority.

 

Amazon QLDB is not a blockchain or distributed ledger technology. On the other hand, QLDB is a purpose-built ledger database that provides a complete and cryptographically verifiable history of all changes made to your application data. 



For more information, see https://aws.amazon.com/qldb/.


**Which Amazon QLDB component represents a complete and immutable history of all the changes to your ledger data?**

History
Current
Journal (Correct)
Ledger
A journal is the chained set of all blocks committed in your ledger. A block is an object that is committed to the journal in a transaction. The journal represents a complete and immutable history of all the changes to your ledger data.



For more information, see https://docs.aws.amazon.com/qldb/latest/developerguide/export-journal.html.


**Which of the following views does Amazon QLDB provide? (Select THREE.)**

User (Correct)
Committed (Correct)
Customer
History (Correct)
There are three views in Amazon QLDB:

User view: Shows the latest non-deleted revision of your application-defined data only. This is the default view in QLDB.
Committed view: Shows the latest non-deleted revision of both your application-defined data and the system-generated metadata. This is the full system-defined table that corresponds directly to your user table.
History view: Shows the revisions from the system-defined view of your table. This view includes both your data and the associated metadata in the same schema as the committed view.
For more information, see https://docs.aws.amazon.com/qldb/latest/developerguide/ledger-structure.html.

**What query language does Amazon QLDB support?**

PL/SQL
PartiQL (Correct)
HTSQL
JPQL
Amazon QLDB supports the PartiQL query language. PartiQL provides SQL-compatible query access across multiple data stores containing structured data, semistructured data, and nested data. 



For more information, see https://docs.aws.amazon.com/qldb/latest/developerguide/ql-reference.html.

**Which of the following components are you billed for when using Amazon QLDB? (Select THREE.)**

Write IOs (Correct)
Read IOs (Correct)
Data transfer (Correct)
SQL query
With Amazon QLDB, you pay only for what you use with no minimum fees or mandatory service usage. You are billed separately for write IO requests, read IO requests, journal storage, indexed storage, and data transfer.



For more information, see https://aws.amazon.com/qldb/pricing/.
