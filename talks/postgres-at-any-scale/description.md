Postgres is a wonderful database. With powerful datatypes like JSONB, extensions like PostGIS, and general emphasis on correctness, it has long been a good choice for applications small and medium. And now with new open source, distributed tools like Citus, Postgres can handle large-scale apps pushing over 500k writes/second. In this session you will find out how to get the most out of your database, and prepare yourself for future growth.

First you'll learn how to take advantage of all Postgres has to offer for small scale apps especially when it comes to keeping data consistent and correct. Careful use of constraints and datatypes keeps your data safe from application changes and bugs.

Next you'll learn tools for keeping applications running well at medium scales. This is where knowing a bit about replication and transaction isolation can pay off. 

And finally you'll learn how to architect your database to take advantage of Citus when the time comes for the big leagues. Distributed databases operate a bit differently from single-node ones, and planning for growth when your data is still small can save a lot of work later on.