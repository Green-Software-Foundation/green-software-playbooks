# Green Software Playbook

## Current status

The goal of this Green Software Playbook is to have some form of guidance to start pushing what we develop to be cleaner and more sustainable.

Below you can find the specific systems we feel we can give guidance on.  Each individual component will have a rubric created so this will be a WIP for now until we figure out the way ratings will works.

## Impacted Systems

### Software as a Service (SaaS)

* Webapps
    * Internal query engines
* Daemons
    * Internal deployment services 
* Data Science Applications
    * Internal ML

### Infrastructure as a Service (IaaS)

* CI/CD
* Caches
* Task Management
  * Airflow
  * Cronjobs
  * etc
* Databases
  * Database queries
  * Data catalog(s)
* Event Streaming 
  * Pipelines

## Playbook Design

### What we would dictate (WIP)

We are still working towards what the rubric will entail but this will be updated once we have more refined the examples below are just some ideas we have in mind

* Emissions 
    * Keep it below a certain usage
* Resource allocation
* Framework choice
    * Django/Angular ect
* Language base
    * Python/Java/C++ ect
* Carbon footprint (this might just fall under emissions)

### Outline of intended framework (WIP)

The rubric will be setup with levels of sustainability that correspond to effort and impact.  In short it will broadly follow:

#### Low effort

These recommendations would include changes that would require minimal effort, such as reduced the allocation of resources where over-allocated.

#### Medium effort

These would include suggestions on changes that would not be considered minimal.  For example, determining the optimal times to run a cronjob, or using a datacenter that is cleaner.

#### High effort

Such suggestions would include changes that would require high effort on the part of product teams, such as using a language or framework that is significantly more efficient than the current one.  For example, switching to Rust, or moving to ARM processors.
