### Rquirement Acceptance Test Mapping Example

Tracking test-requirements mapping is needed so you can see weather a requirement is tested or not. There exists many different ways of describing this relation. You can use [traditional test plans](http://softwaretestingfundamentals.com/test-plan/) or new approaches like [Google 10 minute test plans](https://testing.googleblog.com/2011/09/10-minute-test-plan.html). Also you can manage this relation using test management applications tools like [practitest](https://www.practitest.com/), [qtest](https://www.tricentis.com/products/agile-dev-testing-qtest/) or [TestLink](http://testlink.org/).

#### Requirement Test Mapping Example

One of the simplest way of test requirement mapping is using a table such as this:

|**Requirments**| **Implementation status** | **Related Tests** | **Covered** |
| R001 | State(TODO, Doing, Done) | Tests (T1, T5, T9) | True|
| R002 | State(TODO, Doing, Done) | Tests (T1, T12) | False|
| ... | ... | ... | ... |

#### Notes

* Requirement mapping is an incremental process.
* Coverage calculated for requiremets wich has done status.
* Coverage status checked by all stakeholders such as PM, Test Engineer, ...
* All tests must be executed on each release. (No depreceted or red tests accepted in this list)
* Some showcases or exploratory test could be run manually.
