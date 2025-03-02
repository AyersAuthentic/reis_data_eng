# Database Connectivity Troubleshooting on AWS

This repository contains the necessary files and instructions for completing a hands-on lab focused on troubleshooting database connectivity issues between EC2 instances and an RDS PostgreSQL database on AWS.

## Overview

This lab provides practical experience with:
- Diagnosing and resolving network connectivity issues
- Configuring security groups for database access
- Setting up proper permissions for data transfer from S3
- Creating and populating database tables with data

## Prerequisites

- Basic familiarity with AWS services (EC2, RDS, S3)
- Basic understanding of networking concepts (VPCs, security groups)
- Basic SQL knowledge
- Access to AWS console

## Project Structure

The project is divided into two main sections:

### 1. Fixing Database Connectivity Issues

In this section, you'll troubleshoot and resolve connection issues between an EC2 instance and an RDS PostgreSQL database by:
- Installing the PostgreSQL client
- Diagnosing VPC configuration issues
- Configuring security group rules
- Resolving authentication problems

### 2. Fixing Permission Issues

In this section, you'll:
- Create a database table using SQL
- Configure S3 bucket access policies
- Download data from S3 to EC2
- Import the data into your PostgreSQL database

## Files in this Repository

- `scripts/download_from_s3.py`: Python script to download data from S3
- `sql/ratings_table_ddl.sql`: SQL script to create the ratings table schema
- `sql/copy_data.sql`: SQL script to import data into the database
- `images/`: Directory containing screenshots for guidance

## Learning Objectives

By completing this lab, you will gain experience in:
- Troubleshooting network connectivity in AWS
- Understanding the relationship between different AWS services
- Applying proper security practices when configuring AWS resources
- Writing and executing SQL commands for database operations
- Managing permissions between AWS services

## Additional Resources

For more information on AWS services used in this lab:
- [Amazon RDS Documentation](https://docs.aws.amazon.com/rds/)
- [Amazon EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
- [AWS VPC Documentation](https://docs.aws.amazon.com/vpc/)

