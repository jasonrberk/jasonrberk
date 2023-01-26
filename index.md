# Jason Berk

[https://linkedin.com/in/jasonberk](https://linkedin.com/in/jasonberk)

[jason.r.berk@gmail.com](mailto:jason.r.berk@gmail.com)

I am a highly motivated and self-driven individual looking for a full-stack software engineering position. I bring a long history of delivering impactful contributions to a wide range of projects.  I am passionate about software development and pride myself on writing clean, maintainable code.  I have experience with, and enjoy contributing to, DevOps and CI/CD practices.  Most importantly, I am seeking a position utilizing my experience to contribute technical leadership across the organization.

## Experience

#### 10/2022 - 01/2023 [Bonterra](https://www.bonterratech.com/) - Senior Software Engineer / Architect
  * Provided AWS leadership and mentored teammates on Terraform state management best practices and module design.
  * Rearchitected Java integrations with Docusign and Adobe to implement more secure OAuth strategies and leverage webhook callbacks.

#### 2014 - 10/2022 [NextGear Capital](https://www.nextgearcapital.com/) - Senior Software Engineer
  * Led a complete rebuild of our Graylog cluster utilizing AWS EC2, OpenSearch and SaltStack config management with Python/Jinja.
    * estimated savings of roughly $7,500/month while increasing production log retention
    * all infrastructure managed in Terraform
  * Implemented a custom version of [Atlantis](https://runatlantis.io) allowing over 50 engineers to manage their own Terraform (TF) across roughly 30 AWS accounts.
    * enforces company rules around the PR process and provides auditability
    * built with Node/ExpressJS and deployed as docker containers in AWS Fargate
    * all infrastructure managed in Terraform
  * Implemented custom Java miro-service tooling, allowing 50+ engineers to create new services in a consistent manner.
    * UI built with ReactJS and deployed in Nomad on-premise
    * API build with Java and SpringBoot also deployed in Nomad on-premise and responsible for the creation of repositories, scaffolding code, Jenkins CI/CD jobs, Spring Cloud config stubs and Veracode registration
  * Implemented Veracode integration tooling.  This helped developers identify regressions faster and increased overall security posture.
    * Java / SpringBoot app which uploads build artifacts and schedules scans
    * Java / SpringBoot app which downloads Veracode XML reports and synchronizes findings with our ticketing system
    * Java project using JAXB to generate a library of reusable model objects for binding to Veracode XML report output
  * Tech Lead on a feature team that created numerous AngularJS components while converting our internal .NET client to a modern web application.
  * Collaborated on a set of custom SpringBoot starter libraries.  Specifically responsible for most Spring Security components and OAuth2 solutions using Okta and PingFederate.
    * used by over 90 internal applications
    * provides out of the box solutions / configurations for Spring Cloud Config, Spring Actuators, log aggregation, OAuth2 multi-tenancy, standard integration tests, swagger generation and JDBC connectivity
  * Developed and maintained multiple Terraform modules and Terragrunt tooling at an organization level to enforce policies around AWS usage and security.
    * responsible for the creation of standards and documentation which help provide guidance to the entire engineering department
    * presented at multiple internal AWS learning sessions
  * Proficient in SQL and JPA.
    * capable of using tools to connect directly to an RDBMS to view, query and modify tables, views, functions and stored procedures
    * experience with Liquibase and Flyway tools

#### 2013 - 2014 Interactive Intelligence (ININ) - Senior Software Engineer
  * Member of an integrated delivery team, working in an agile environment to design, develop, and maintain integrations between 3rd party products and internal tools.  Extensive experience with AngularJS.
  * Contributed to the next generation of cloud native call center tools intended to replace all customer managed on-premise solutions.  Primary languages were Java and KnockoutJS.

#### 2008 - 2013 Purdue Federal Credit Union - Software Developer
  * Developed numerous online banking tools.  My most impactful contribution was the complete rewrite of the monthly statement generation process using Java, *NIX tools and MySQL.
    * Converted an overly complex system with many points of unrecoverable failure and a multi-day runtime into a streamlined process that ran in hours
    * By using better data extraction techniques, RDS storage, *NIX tooling and PDF generation tools I was able to convert exported server data at month end to online statements in the same day
    * Achieved roughly $15,000/month in bottom line savings by overhauling the statement printing and mailing process
    * This process also provided the ability for targeted marketing and better analytics

#### 2000 - 2007 Purdue University - Software Developer
  * Gained experience in Apache, Perl, Java and *NIX tools.  Worked directly with WebCT integrations and for the IAM department to increase software security practices at the university across different departments.

## Education
  * 1995 - 1999 Purdue University - Computer Technology, Bachelor of Science

## Projects
  * [Borrowed Time EAP](https://borrowedtimeeap.com) - Web Designer / Maintainer
    * Built with NuxtJS using Tailwind CSS and hosted on GitHub Pages.
