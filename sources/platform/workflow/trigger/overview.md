page_main_title: Overview
main_section: Platform
sub_section: Configuration
sub_sub_section: Triggers
page_title: Unified Pipeline Jobs
page_description: Triggers are used to manually start a Job.
page_keywords: Deploy multi containers, microservices, Continuous Integration, Continuous Deployment, CI/CD, testing, automation, pipelines, docker, lxc

# Triggers

Triggers are used to manually start a job. They are resources, but, unlike other resource types, updating a trigger in the YML will start any dependent jobs.

<img src="/images/platform/configuration/triggerJob.png" alt="Triggering a manual job through a resource" style="width:400px;vertical-align: middle;display: block;margin-left: auto;margin-right: auto;"/>

You could also achieve this by triggering through UI, but this is for those who like to do it with code.

They are typically used in these cases

* A manual CI build
* User driven Release Management process
* Backups
* Scale the service up or down


## Further Reading
* [Working with Triggers](/platform/tutorial/workflow/crud-trigger)
