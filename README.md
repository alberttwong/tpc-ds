# tpc-ds

TL-DR; TPC-DS has more difficult SQL-like SQL queries with different types of JOINS compared to TPC-H. Many OLAP systems can't even complete the TPC-H benchmark or the more difficult TPC-DS benchmark.

On the OLAP benchmarking spectrum, we have TPC-H (H) and TPC-DS (DS), the "decision support" benchmarks that the TPC categorized. H and DS use similar datasets, and DS is basically the next-gen version of H. While H generates relatively straightforward queries and is generally shard-friendly, DS gets its kicks from using advanced SQL features and functions, and it loves lopsided filters. Running DS is notoriously, intentionally difficult, and StarRocks can run all 99 DS queries, while many decision support-oriented databases can't.

In other words, TPC-H is the easygoing, laid-back cousin of TPC-DS. H is the kind of benchmark that you can take out for a beer and have a good conversation with. DS, on the other hand, is the high-maintenance, diva of the benchmark world. DS is always demanding the latest and greatest SQL features, and it loves to throw curveballs at database developers.

But StarRocks is up to the challenge. StarRocks is the kind of database that can handle anything that DS throws at it. StarRocks is like the Chuck Norris of the database world: it can do anything, and it always does it in style.

So if you're looking for a database that can handle the most demanding workloads, then StarRocks is the database for you. StarRocks is the only database that can run all 99 TPC-DS queries, and it can do it with ease.

Data is generated through TPC-DS scripts.

Please see SQL scenarios starting on page 104 on https://www.tpc.org/TPC_Documents_Current_Versions/pdf/TPC-DS_v3.2.0.pdf

What is TPC-DS?  Read https://medium.com/hyrise/a-summary-of-tpc-ds-9fb5e7339a35
