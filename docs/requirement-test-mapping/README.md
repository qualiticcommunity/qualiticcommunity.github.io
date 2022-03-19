# Requirement Acceptance Test Mapping

Tracking test-requirements mapping is needed so you can see wether a requirement is tested or not. There exists many different ways of describing this relation. You can use [traditional test plans](http://softwaretestingfundamentals.com/test-plan/) or new approaches like [Google 10 minute test plans](https://testing.googleblog.com/2011/09/10-minute-test-plan). Also you can manage this relation using test management applications tools like [practitest](https://www.practitest.com/), [qtest](https://www.tricentis.com/products/agile-dev-testing-qtest/) or [TestLink](http://testlink.org/).

Generally, the following definitions are important:
- The set of **all requirements** is defined based on the requirements which already has been developed by the team.
- The requirements may also include non-functional requirements such as security and scalability.
- In the end, a table like Table #1 must be presented by dev team.
- The percentage of requirement-test mapping is calculated by:
  ```
  (Implemented requirements having tests) / (Total implemented requirements)
  ```

## Requirement Test Mapping Example

One of the simplest way of test requirement mapping is using a table such as this:

| **Requirements** | **Implementation status** | **Related Tests** | **Covered** |
| :--              | :--                       | :--               | :--         |
| R001 | State(TODO, Doing, Done) | Tests (T1, T5, T9) | True|
| R002 | State(TODO, Doing, Done) | Tests (T1, T12) | False|
| ...  | ...                      | ...             | ...  |

## Notes
- Requirement mapping is an incremental process.
- Coverage calculated for requirements that have done status.
- Coverage status checked by all stakeholders such as PM, Test Engineer, ...
- All tests must be executed on each release. (No deprecated or red tests accepted in this list)
- Some showcases or exploratory test could be run manually.
