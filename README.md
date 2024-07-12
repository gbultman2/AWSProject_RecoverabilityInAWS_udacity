# AWSProject_RecoverabilityInAWS_udacity
Recoverability project for the udacity nanodegree - AWS cloud architect

## Introduction
This project demonstrates the creation of highly available solutions to common use cases, focusing on data durability and recovery using AWS. The project involves building a Multi-Availability Zone, Multi-Region database and a versioned website hosting solution.

## Table of Contents


## Part 1 - Data Durability and Recovery
In this part, I set up the network and established a multi-az RDS database with a read replica in another region

### VPC Setup
To start, I used the provided yml file and used cloud formation to set up the networking in the us-east-1 and us-west-2 regions.  The setup included two private and two public subnets across two availability zones in two different regions.

![VPC Setup - Primary VPC](screenshots/primary_Vpc.png)
