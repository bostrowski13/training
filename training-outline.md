# training paths

This document is intended to outline the goals and various training paths for teams and individuals guiding and delivering applications for the business to the public cloud.

- [training paths](#training-paths)
  - [Preface (Why is this important)](#preface-why-is-this-important)
  - [Leadership (+ Non-Technical) Team Requirements](#leadership--non-technical-team-requirements)
    - [Time Requirements](#time-requirements)
    - [When should leaders dedicate time](#when-should-leaders-dedicate-time)
    - [Engagement](#engagement)
      - [What happens before the engagement](#what-happens-before-the-engagement)
      - [What happens during engagement](#what-happens-during-engagement)
      - [Engagement Deliverables](#engagement-deliverables)
  - [Development Team Requirements](#development-team-requirements)
    - [Time Requirements](#time-requirements-1)
    - [When should teams dedicate time](#when-should-teams-dedicate-time)
    - [Engagement](#engagement-1)
      - [What happens before the engagement](#what-happens-before-the-engagement-1)
      - [What happens during engagement](#what-happens-during-engagement-1)
      - [Engagement Deliverables](#engagement-deliverables-1)
  - [Learning Paths](#learning-paths)
    - [Leadership and Non-Technical](#leadership-and-non-technical)
    - [Developer I](#developer-i)
    - [Developer II](#developer-ii)

## Preface (Why is this important)

Infrastructure is no longer a physical asset and an operational and service management problem.  Infrastructure in the cloud is a software design and a development management problem.  This is a critical component in the in the facilitation to shift-left and adopt other DevOps Principals.

With these paradeigm shifts in mind, an investment in an entirely new set of technology, and people with the right training uisng that techonology, are needed to build solutions using these new technologies.  

Investing in people is important for a successful cloud transformation.  Roles and responsilibilties change when moving to Cloud, and this can lead to discomfort and resistance in the transformation.

To help avodd these pitfalls and speed the rate of adoption, an investment in personal skills development and understanding of the purpose and goals of the cloud is needed at all levels of the business.  This includes not only developers and engineers, but managers, analysis, and other non-technical persons involved in delivering software.

This also provides people an opportunity to learn and take on new opportunities, as well as evolve their career paths.  However, this needs to happen in a way they are comfortable with, find valuable, and are excited about.

The courses offered in the curriculum are meant to provide a wide variety of views and knowledge regarding the aspects of this transformation for individuals in a veriety of positons.

It includes technical and non-technical training, as well as other concepts for facilitating the paradeigm shift needed to successfully transition all aspects of continuous delivery within a cloud-based ecosystem.

The remainder of this document will cover the process and requirements for teams and individuals moving to cloud.

## Leadership (+ Non-Technical) Team Requirements

### Time Requirements

At a minimum, an individual who is in a leadership position should dedicate as much time as necessary to complete the Leadership training path.

These courses include high level goals and values for the adoption of the concepts for successful cloud transition and/or migration.  Depending on the maturity of the team or individual, this may require more time.

### When should leaders dedicate time

The time should be taken immediately, especially if a project is already in-flight, or at least 1 month prior to the consideration of any projects.

### Engagement

Courses will be offered at regular intervals, or can be scheduled as needed.  This should be time spent undersatnding how the public cloud can be used as a transformative technology, what paradeigm shifts are needed to succeed, and how the shifting roles and repsonsibilities should change for a successful cloud migration or adoption.

#### What happens before the engagement

* Self-paced research
* Initial Consult with SMEs in DevOps/Cloud/Culture areas

#### What happens during engagement

* A SME in Cloud and DevOps assists in training the team or individual following the recommended learning paths outlined below.
* Ongoing consult with SMEs in DevOps/Cloud/Culture areas, as needed.

#### Engagement Deliverables

At the end of the engagement period, a team or individual should have:

* An understanding of how AWS is implemented against industry best practices
* An undersatnding of the Cultural and Technical shifts necessary for a successful cloud migration or adoption.
* The ability to understand Cloud and DevOps practices, including how they can help deliver better, more secure, and more reliable applications.

## Development Team Requirements

### Time Requirements

At a minimum, an entire development team should dedicate at least 1 full 2 week sprint to the introduction and adoption of the concepts contained on the learning paths.  Depending on the maturity of the team or individual, this may require more time.

### When should teams dedicate time

At least 1 full 2 week sprint before any development of workloads hosted in the cloud occur.  Depending on the maturity of the team or individual, this may require more time.

### Engagement

An SME should embed themselves in a development team for at least 1 full 2 week sprint.  They should group and/or partner program with the team using the future desired workload the team intends to use in the cloud.  This removes the need for unecessary time spent on POCs and MVPs, and provides real value towards a codebase a team can mature as they prepare for the deployment date.  Depending on the maturity of the team or individual, this may require more time.

#### What happens before the engagement

* AWS Account setup (if needed)
* SNow Requests for Privledged Accounts (x-ids) and Access for Technical individuals on the team for their accounts
* SNow Requests for Required Software (python, terraform, go, docker, etc etc)
* Local IDE Setup Assistance

#### What happens during engagement

* Local IDE Setup Troubleshooting (if necessary)
* Time dedicated to the coursework in the Learning Paths outlined below.
* Helping the team understand what it takes to delilver an application through the entire SDLC.
* All items included in a project that help deliver and maintain their application.
* Teaching the team to be self-sufficient; learning from their successes and failures together during the engagement period.
* The codebase is iterated on daily, and continuously deployed using the Deployment pipeline for Cloud, helping actively adopting Agile methodologies.
* A list of common resources (documenation) is given to the team, such as:
  * Terraform Starter
  * AWS Account Listing
  * AWS VPC CIDR Codes
  * Security Standards documents for Services
  * Terraform Modules
* Helping fill the knowledge gaps to teams about Cloud and related technologies to grow a culture of understanding and enablement.

#### Engagement Deliverables

At the end of the engagement period, a team should have:

* An understanding of how applications are implemented and delivered in the cloud.
* At least 30-40% of their application and corresponding infrastructure codified and stored in source control
* A robust CI/CD Pipeline for continuing work toward a v1 deliverable of their application
* Resources for ongoing learning

## Learning Paths

### Leadership and Non-Technical

**Target Audience**: The target of this path is for individuals entirely new to the cloud and/or DevOps concepts, who may not be interested in the lower level technical concepts and design, and wnat to know what value can be added by using these technologies and methodologies.

At a very basic level, individuals and/or teams should have attended, or have proficiency in the content of, the following courses.

| Course # | Overview |
|---|---|
| AWS-100 | Cloud Concepts and Shift Left |
| IAC-100 | Introduction to Infrastructure as Code |

### Developer I

**Target Audience**: This track is intended for individuals currently in operations or support roles, as well as developers who are building or migrating a workload to the cloud that want to build a solid foundation of Cloud and DevOps skillsets.

At a very basic level, individuals and teams should have attended, or have proficiency in the content of, the following courses.

| Course # | Overview |
|---|---|
| AWS-100 | Cloud Concepts and Shift Left |
| AWS-101 | Account Structure, Delivery Pipeline Intro |
| AWS-102 | Delivery Pipeline Deeper Dive |
| AWS-103 | Intro to Serverless and FaaS Concepts and Technology |
| AWS-104 | AWS KMS and IAM Basics |
| AWS-105 | Cloudwatch Logs, Metrics and Basic Troubleshooting |
| IAC-100 | Introduction to Infrastructure as Code |
| IAC-101 | Terraform Basics |
| IAC-102 | Terraform Workflow, workspaces, and Inputs and Outputs |
| IAC-103 | Terraform Metaparameters and Lifecycle |

### Developer II

**Target Audience**: Individuals who are proficient in all concepts in Developer I, who want to become an expert in delivering solutions to the cloud following DevOps methodologies.

| Course # | Overview |
|---|---|
| IAC-201 | Fix your own Terraform problems |
| CD-201  | Fix your own Pipeline problems |
