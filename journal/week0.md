# Week 0 — Billing and Architecture

## General description

This week we will set up AWS account, register in a few services needed to implement this bootcamp, initiate our github repository based on Andrew template and begin to familiarize ourselves with the bootcamp stuff and tools.

## First steps

- [x] **Create an AWS account**: done by the organization that I belongs to (https://aws.amazon.com).
- [x] **Create an AWS IAM user**: added by organization's administrator.
- [x] **Create a billing alarm**: configured by organization's administrator.
- [x] **Create a budget**: assigned by organization's administrator.
- [x] Open a support ticket and request a service limit at *AWS Console -> Support center -> Create case -> Looking for service limit increases?*.
- [X] Create a Github repository (https://www.github.com).
- [X] Login into Gitpod with github account and create a Gitpod workspace (https://www.gitpod.io).
- [x] Explore github.com/codespaces as an alternative of a CDE.
- [x] Momento: obtain AWS token and configure cli (https://www.gomomento.com).
- [X] Create Lucidchart account (https://www.lucidchart.com).
- [X] Create a free-tier Honeycomb account (https://www.honeycomb.io).
- [X] Create a free-tier Rollbar account (https://www.rollbar.com).

## Install aws-cli

> curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
> unzip awscliv2.zip
> cd aws
> ./install -i ~/.local/aws-cli -b ~/.local/bin

Re-login and command **aws** is available

## AWS Well-Architected Tool
Review pillars to get involved with architectural best practices.

1. Operational Excellence: https://docs.aws.amazon.com/wellarchitected/latest/operational-excellence-pillar/welcome.html
2. Security: https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html
3. Reliability: https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/welcome.html
4. Performance Efficiency: https://docs.aws.amazon.com/wellarchitected/latest/performance-efficiency-pillar/welcome.html
5. Cost Optimization: https://docs.aws.amazon.com/wellarchitected/latest/cost-optimization-pillar/welcome.html
6. Sustainability: https://docs.aws.amazon.com/wellarchitected/latest/sustainability-pillar/sustainability-pillar.html

### Appendix: Questions and best practices
https://docs.aws.amazon.com/wellarchitected/latest/framework/appendix.html

## Conceptual diagram
Create the diagram with Lucidchart tool to describe the functionality of what we plan to build during this bootcamp.

==todo: add diagram image==

## Architectural diagram
Create the diagram with Lucidchart tool of the CI/CD logical pipeline.

==todo: add diagram image==
