# tpc-ds

On the opposite end of the spectrum, we have TPC-H (H) and TPC-DS (DS), categorized by the TPC as “decision support” benchmarks. H and DS use similar datasets, and DS is effectively the next-generation version of H. While H generates fairly straightforward queries and tends to be shard-friendly, DS thrills in its use of advanced SQL features and functions and exhilarates in its lopsided filters. Running DS is notoriously, purposefully difficult, and StarRocks can run all 99 DS queries, while many decision support-oriented databases cannot.

Data is generated through TPC-DS scripts.

Please see SQL scenarios starting on page 104 on https://www.tpc.org/TPC_Documents_Current_Versions/pdf/TPC-DS_v3.2.0.pdf

What is TPC-DS?  Read https://medium.com/hyrise/a-summary-of-tpc-ds-9fb5e7339a35
