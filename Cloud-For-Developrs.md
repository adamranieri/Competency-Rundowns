# Cloud for Developers
By Adam Ranieri


### Definition
Cloud for Developers covers the essential building blocks of *deploying* full-stack applications on a cloud service. There should be a mental model of how the different levels of an application could be deployed on a cloud service. Low-level infrastructure details like CIDR blocks, networking are not emphasized but are intermediary steps to deploying applications. General cloud ideas like scaling, IAM, IaaS, PaaS and SaaS are understood but not mastered. The rundown is cloud and language agnostic. A Rosetta Stone of cloud techs is found [here](https://github.com/adamranieri/cloud-rosetta-stone/blob/master/cloud-rosetta-stone.md).

### Abilities
- Can create and use a SQL database
  - AWS (RDS)
  - GCP (Cloud SQL)
  - Azure (SQL Database)
- Can create a VM and deploy a backend web app on it
  - AWS (EC2)
  - GCP (Compute Engine)
  - Azure (Virtual Machine)
- Can statically host a front-end using object storage
  - AWS (S3)
  - GCP (Cloud Storage)
  - Azure (Blob Storage)
- Can transfer their local web apps to work entirely in the cloud

### Trainer Advice
- Have associates sign up and sign into the cloud provider the day BEFORE you start using it.
  - Some associates might have billing/email problems that could take hours to fix if you are waiting for them.
- Cloud Technologies tend to be very UI intensive as you show things off.
  - Expect changes in the UI and differences between users
- Cloud resources can take time to spin up.
- ALWAYS do the example by yourself before trying it in the batch
  - It is very easy to forget just 1 thing and the example is broken
- Try to hook in as much DevOps as is feasible
  - Use GitHub actions or Jenkins to show of the synergy
- Remind associates to shut down any resources they do not need as soon as examples end

## Assessment

### Green Flags
- Associate can debug their own problems
- Associate is able to rule out errors in deploying their app.
- Associate can deploy an application with 0 help from the trainer or another associate.

### Red Flags
- Associate has never had a deployed app at any point
