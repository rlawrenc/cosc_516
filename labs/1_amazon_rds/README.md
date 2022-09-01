# COSC 516 - Cloud Databases<br/>Lab 1 - MySQL on Amazon RDS

## Setup

Create a Amazon AWS free tier account at: [https://aws.amazon.com/free](https://aws.amazon.com/free).

The free tier account allows for free trials forever and 12-months free offers from your sign up period. You will need an email address to use. The sign-up also asks for a credit card. If you do not have a credit card, then a pre-paid credit card with a small amount should work.

## AWS Console

Login to AWS. In the AWS console, select `Databases` then `RDS`.

## Amazon RDS

Click on `Create database`. Select `MySQL` as the engine and `Free tier`. For database identifier use `mysql516`. Select a master password for your database. The instance configuration is `db.t3.micro`. Leave storage as `General Purpose SSD`.

For Connectivity, make sure to have public access as `Yes`. Select `Create new VPC` and `DB Subnet Group`. 


Leave database authentication as `Password authentication`.

