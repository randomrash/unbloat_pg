# unbloattable.sh
Script for automatic detection and removal bloats in PostgreSQL Tables
User manual. Before using, you need to install
on Debian-based Linux OS with apt-get install libdbi-perl libdbd-pg-perl
RedHat/Centos with yum install perl-Time-HiRes perl-DBI perl-DBD-Pg
and pgcompacttable and the pgstattuple extension. create script in postgres user's home directory
The author of the query used in the script to search for bloat >> https://github.com/pgexperts/pgx_scripts/blob/master/bloat/table_bloat_check.sql
