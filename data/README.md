# Data

If using an external dataset (that doesn't come in an R package), place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, codebook, etc.

The codebook for your data file(s) using the following format.

## job_postings.csv

| Variable                   | Description                                                                                       |
|:---------------------------|:--------------------------------------------------------------------------------------------------|
| job_id                     | unique job ID as defined by LinkedIn identifying the particular offering (ID)                     |
| company_id                 | unique company ID as defined by LinkedIn identifying the particular company offering the job (ID) |
| title                      | job title as found in the LinkedIn post (ID)                                                      |
| description                | job description (ID)                                                                              |
| job_posting_url            | URL to the job posting on a platform (ID)                                                         |
| application_url            | URL where applications can be submitted (ID)                                                      |
| skills_desc                | description detailing required skills for job (ID)                                                |
| max_salary                 | maximum salary offered in the position (numerical)                                                |
| med_salary                 | median salary offered in the position (numerical)                                                 |
| min_salary                 | minimum salary offered in the position (numerical)                                                |
| applies                    | number of applications that have been submitted (numerical)                                       |
| views                      | number of times the job posting has been viewed (numerical)                                       |
| original_listed_time       | original time the job was listed, in UNIX time (numerical)                                        |
| listed_time                | time when the job was listed, in UNIX time (numerical)                                            |
| closed_time                | Time to close job listing, in UNIX time (numerical)                                               |
| expiry                     | expiration date or time for the job listing, in UNIX time (numerical)                             |
| pay_period                 | pay period for the salary, hourly, monthly, yearly (categorical)                                  |
| formatted_work_type        | type of work, fulltime, parttime, contract (categorical)                                          |
| formatted_experience_level | job experience level, as entry, associate, executive, etc. (categorical)                          |
| compensation_type          | if the type of compensation for the job is a base salary or not (categorical)                     |
| location                   | job location, in city, state format (categorical)                                                 |
| application_type           | Type of application process, offsite, complex/simple onsite (categorical)                         |
| posting_domain             | domain of the website with application (description)                                              |
| sponsored                  | whether the job post is promoted by a sponsor or not (categorical)                                |
| work_type                  | type of work associated with the job, full time or contract (categorical)                         |
| currency                   | if the currency in which the salary is provided is in the US or not (categorical)                 |
| remote_allowed             | whether job permits remote work (categorical)                                                     |

## benefits.csv

| Variable | Description                                                                   |
|:---------|:------------------------------------------------------------------------------|
| job_id   | unique job ID as defined by LinkedIn identifying the particular offering (ID) |
| type     | type of benefit provided (401K, Medical Insurance, etc) (categorical)         |

## employee_counts.csv

| Variable       | Description                                                                                       |
|:---------------|:--------------------------------------------------------------------------------------------------|
| company_id     | unique company ID as defined by LinkedIn identifying the particular company offering the job (ID) |
| employee_count | number of employees at company (numerical)                                                        |
| follower_count | number of company followers on LinkedIn (numerical))                                              |
