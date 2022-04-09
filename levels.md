# Maturity Levels
This is what we use as quality maturity levels.

## Level 1

| **Item**          | **Description** |
| :--               | :--             |
| **[T001](catalog/test/T001)** | Test coverage is measured at the [commit stage](/QMM-in-detail#commit-stage) |
| **[B001](catalog/build_ci/B001)** | All CI/CD scripts are kept in version control |
| **[T016](catalog/test/T016)** | No release with red tests |

---

## Level 2

| **Item**          | **Description** |
| :--                | :--             |
| **[T002](catalog/test/T002)** | Commit stage test coverage > 10% |
| **[T007](catalog/test/T007)** | Classify tests as commit, acceptance, and performance |
| **[T011](catalog/test/T011)** | There are acceptance tests for at least one feature upon main use cases |
| **[B002](catalog/build_ci/B002)** | A specific code style is enforced for main programming languages |
| **[B004](catalog/build_ci/B004)** | Compiler warnings are prevented |
| **[E001](catalog/environment/E001)** | All direct external dependencies for the software product are specified using fixed versions in version control and also managed with tools/scripts in version control |
| **[E012](catalog/environment/E012)** | Secrets are not stored in version control |
| **[D001](catalog/delivery/D001)** | Deployment frequency is once per month |
| **[D005](catalog/delivery/D005)** | Lead time for changes is less than six months |
| **[D009](catalog/delivery/D009)** | Time to restore service is less than one month |
| **[D013](catalog/delivery/D013)** | Change failure rate is less than 60% |

---

## Level 3

| **Item**          | **Description** |
| :--               | :--             |
| **[T003](catalog/test/T003)** | Commit stage test coverage > 20% |
| **[B005](catalog/build_ci/B005)** | Available analysis tools on new code are actively used, as submit gate (50% sonar-way, zero issue, incremental) |
| **[T012](catalog/test/T012)** | There are acceptance tests for each new feature |
| **[T013](catalog/test/T013)** | "Requirement - Acceptance Test" mapping coverage > 5% |
| **[E002](catalog/environment/E002)** | Automated application deployment from scratch |
| **[E003](catalog/environment/E003)** | Automated application upgrade |
| **[E013](catalog/environment/E013)** | All configuration in version control and all production configs from version control |
| **[E006](catalog/environment/E006)** | Data is migrated using versioned script only |
| **[D002](catalog/delivery/D002)** | Deployment frequency is once per week |
| **[D006](catalog/delivery/D006)** | Lead time for changes is less than one month |
| **[D010](catalog/delivery/D010)** | Time to restore service is less than one week |
| **[D014](catalog/delivery/D014)** | Change failure rate is less than 45% |
| **[E010](catalog/environment/E010)** | Same process (scripts) to deploy to every environment |

---

## Level 4

| **Item**          | **Description** |
| :--               | :--             |
| **[T004](catalog/test/T004)** | Commit stage test coverage > 50% |
| **[T014](catalog/test/T014)** | "Requirement - Acceptance Test" mapping coverage > 20% |
| **[B006](catalog/build_ci/B006)** | Available analysis tools are actively used on new code (80% of sonar-way) |
| **[B007](catalog/build_ci/B007)** | Build environment can be automatically created from version control |
| **[B008](catalog/build_ci/B008)** | No manual configuration of CI/CD agent machines |
| **[E004](catalog/environment/E004)** | Automated infrastructure provisioning from scratch |
| **[E007](catalog/environment/E007)** | Automated data migration while deploying |
| **[E005](catalog/environment/E005)** | Automated infrastructure upgrade |
| **[E014](catalog/environment/E014)** | All transitive dependency versions are defined |
| **[D003](catalog/delivery/D003)** | Deployment frequency is once per day |
| **[D007](catalog/delivery/D007)** | Lead time for changes is less than one week |
| **[D011](catalog/delivery/D011)** | Time to restore service is less than one day |
| **[D015](catalog/delivery/D015)** | Change failure rate less than 15% |

---

## Level 5

| **Item**          | **Description** |
| :--               | :--             |
| **[T015](catalog/test/T015)** | "Requirement - Acceptance Test" mapping coverage > 50% |
| **[E008](catalog/environment/E008)** | Data migrations are tested |
| **[D004](catalog/delivery/D004)** | Deployment is on-demand (multiple deploys per day) |
| **[D008](catalog/delivery/D008)** | Lead time for changes is less than one hour |
| **[D012](catalog/delivery/D012)** | Time to restore service is less than one hour |
| **[E009](catalog/environment/E009)** | Data migration can be rolled back, automatically |
