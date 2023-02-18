# Week 0 — Billing and Architecture

## Required Homework ##

### Lucid Chart Diagram ###
image here

```
https://lucid.app/lucidchart/32a60b70-65bb-49ee-a181-1f36be530ea9/edit?viewport_loc=-710%2C353%2C3072%2C1293%2C0_0&invitationId=inv_dfeed5a0-adb3-48db-82de-8bb0cc67f2e4

```

### AWS CLI ###

I was able to install AWS CLI. I also researched about how to use CLI for multiple users and came across --profile parameter. I created 2 IAM users(farooq1 and farooq2) and generated 2 set of credentials. I was able to switch AWS CLI credentials by using --profile parameter.

aws s3 ls --profile farooq1 
aws s3 ls --profile farooq2

