# rdsler

creates aws rds the easy way


## show all rds in every region

bin/rdsler list-all

bin/rdsler ensure eu-west-1 db-1
bin/rdsler modify eu-west-1 db-1 --capacity=2:2 --backup-retention-period=1
bin/rdsler delete eu-west-1 db-1


psql --dbname postgres://user:pass@rdsler-db-1.cluster-c1eew5nyqpdr.eu-west-1.rds.amazonaws.com:5432/postgres


## envs

bin/rdsler ensure eu-west-1 vodka-1