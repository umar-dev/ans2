WE can achived table partitioning by following  type of partition in MYSQL 8.0

RANGE partitioning.  This type of partitioning assigns rows to partitions based on column values falling within a given range.

LIST partitioning.  Similar to partitioning by RANGE, except that the partition is selected based on columns matching one of a set of discrete values. 

HASH partitioning.  With this type of partitioning, a partition is selected based on the value returned by a user-defined expression that operates on column 
values in rows to be inserted into the table. The function may consist of any expression valid in MySQL that yields a nonnegative integer value. 


KEY partitioning.  This type of partitioning is similar to partitioning by HASH, except that only one or more columns to be evaluated are supplied,
 and the MySQL server provides its own hashing function. These columns can contain other than integer values,
 since the hashing function supplied by MySQL guarantees an integer result regardless of the column data type. 
