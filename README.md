# vpc-3-tier-with-remote-backend
# This is 3-tier vpc architecture with 2 public, private and database subntes
# Across 2 azs
# the state file are store in s3 buckets with lock using Dynamodb
# NAT gateway is created in puliblic subnets and attched the private subnets route tables.
# this vpc will be used by other project as part deploying the aws resources. 