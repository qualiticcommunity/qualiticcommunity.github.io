# QMM, in detail
Qualitic Maturity Model consists of [5 levels](/levels); the first level introduces the initial steps to get in the picture of quality; whereas level 5 indicates the ultimate state of quality.  
Each level includes a list of maturity items, grouped together. [Maturity items](/items-catalog) are the building blocks of QMM; each of which indicates a specific hint about what should be performed, for the sake of quality.  
A product is considered to be developed at level _N_ of quality, if and only if all items from level 1 to _N_ are achieved.  

## Baseline CI Pipeline
Qualitic assumes that the product has a _[Continuous Integration](https://www.atlassian.com/continuous-delivery/continuous-integration)_ pipeline, facilitating its maintenance and development process.  
It's also assumed that the pipeline has at least five (abstract) steps, as mentioned in the next sections.

### 1. Commit Stage
It's the first time a developer introduces a new change to the source code repository. There can be some automatic checks validating the change.  
Generally, the commit stage ensures that a change is worth reviewing by a human-being; since many trivial issues (like compile error) can be caught by a machine, instead of a developer.  
> One machine can do the work of fifty ordinary men. No machine can do the work of one extraordinary man.  
<small>_Elbert Hubbard, American writer and philosopher_</small>  

Although many non-trivial issues also can be checked automatically (with more complexity, of course), it's recommended to keep this stage fast enough to deliver early feedback to the developer, more rapidly.

### 2. Code Review
As mentioned above, not all issues of a suggested change are detected by the commit stage, and hence it needs a manual review - usually by a co-worker.

### 3. Acceptance Test Stage
When the change has been checked against trivial/fast-discoverable issues, reviewed by another developer, and merged into the source code repository (mainline), it's time to perform [acceptance tests](https://www.agilealliance.org/glossary/acceptance/) in order to be more confident about the recently-merged change. It ensures end-user functional requirements are satisfied, after all. The _Acceptance Test Stage_ is a place for this activity.

### 4. Performance Test Stage
Although most user requirements are of functional type, usually there are also some [non-functional](https://www.guru99.com/non-functional-requirement-type-example) ones, even if not declared formally. As an example, a simple phone book application is supposed to save a new phone number in a timely manner, even if it's not specified anywhere. (i.e. no one waits for an hour for a single phone number to be saved!)  
This stage is the place for running non-functional tests, specifically [performance tests](https://www.guru99.com/performance-testing).  
Performance and Acceptance tests can also run in parallel in a single stage.

### 5. Staging
The final stage, before releasing the change into production, is named _Staging_. Here the (recently-changed) product is deployed to a production-like environment (with the exact architecture, infrastructure, etc. of the production). It helps identify even more issues missed in the previous stages. Furthermore, it's a kind of test for the production deployment procedure itself.


## Categories
The items of the maturity model focus on different sides of product development. Generally, each item has one of the below categories:

### Test
This category is about software testing, surprisingly.  
Code coverage, different types of tests, etc. are of this category.

### Environment
Managing infrastructure, deployment strategies, update policies, etc. are all items of the Environment category.

### Build and Continuous Integration
This category demonstrates concerns about the build, packaging, compatibility, versioning, and so on for the product.
Preventing compiler warning, unified code style, and static code analysis are examples of items in this category.

### Delivery
This category is about how the product is delivered to the end-users. Currently, there are four metrics for it that are described below.

##### Deployment Frequency
How often does your organization deploy code?

##### Lead Time
How long does it take to go from code commit to code successfully running in production?

##### Time to Restore
How long does it generally take to restore service, when a service incident occurs.

##### Change Failure Rate
What percentage of changes to production or released to users result in degraded service (e.g., lead to service impairment or service outage) and subsequently require remediation (e.g., require a hotfix, rollback, fix forward, or patch).  

At each level, the desired value of these metrics is noted as a maturity item.

## QMM, in action
We've already learned the prerequisites of using QMM. Let's dive in to the [Levels of Maturity](/levels).
