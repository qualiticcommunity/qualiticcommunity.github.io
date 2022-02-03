# Maturity Levels
This is what we use as quality maturity levels.

## Level 1

| **Item**          | **Description** |
| :--                | :--             |
| **[T001](catalog/test/T001)** | Measure Test Coverage On Commit Stage. |
| **[T005](catalog/test/T005)** | Incremental Commit Stage Test Coverage > 10%. |
| **[B001](catalog/build_ci/B001)** | All CI/CD scripts are in VC (CI Config in Code). |
| **[T016](catalog/test/T016)** | No Release with Red Tests. |

---

## Level 2

| **Item**          | **Description** |
| :--                | :--             |
| **[T006](catalog/test/T006)** | Incremental Commit Stage Test Coverage > 50%. |
| **[T002](catalog/test/T002)** | Commit Stage Test Coverage > 10% (At Least Daily). |
| **[T007](catalog/test/T007)** | Classify Tests as Commit, Acceptance, and Performance. |
| **[T011](catalog/test/T011)** | Acceptance Tests For at Least One Feature Upon Main Use Cases (Fully Automated in CI Script). |
| **[B002](catalog/build_ci/B002)** | Enforcing a Specific Code Style for Main Programming Languages. |
| **[B004](catalog/build_ci/B004)** | Prevent Compiler Warning. |
| **[E001](catalog/environment/E001)** | All Direct External Dependencies for The Software Product Are Specified using Fixed Versions in Version Control and also Managed with Tools/Scripts in Version Control. |
| **[E012](catalog/environment/E012)** | Do Not Store Your Secrets in Your Version Control. |
| **[D001](catalog/delivery/D001)** |Deployment Frequency is Once Per Month. |
| **[D005](catalog/delivery/D005)** | Lead Time for Changes is Less Than Six Months. |
| **[D009](catalog/delivery/D009)** | Time to Restore Service is Less Than One Month. |
| **[D013](catalog/delivery/D013)** | Change Failure Rate Less Than 60 Percent. |

---

## Level 3

| **Item**          | **Description** |
| :--                | :--             |
| **[T003](catalog/test/T003)** | Commit Stage Test Coverage > 50%. |
| **[B005](catalog/build_ci/B005)** | Actively Use Available Analysis Tools On New Code As Submit Gate (50% of sonar-way, Incremental, Zero Issue). |
| **[T012](catalog/test/T012)** | Acceptance Tests For Each New Feature. |
| **[T013](catalog/test/T013)** | Requirement - Acceptance Test Mapping > 5%. |
| **[E002](catalog/environment/E002)** | Automated Application Deployment From Scratch. |
| **[E003](catalog/environment/E003)** | Automated Application Upgrade. |
| **[E013](catalog/environment/E013)** | All Configuration In Version Control & All Production Configs From Version Control. |
| **[E006](catalog/environment/E006)** | Data Is Migrated Using Versioned Script Only. |
| **[D002](catalog/delivery/D002)** | Deployment Frequency is Once Per Week. |
| **[D006](catalog/delivery/D006)** | Lead Time for Changes is Less Than One Month. |
| **[D010](catalog/delivery/D010)** | Time to Restore Service is Less Than One Week. |
| **[D014](catalog/delivery/D014)** | Change Failure Rate Is Less Than 45 Percent. |
| **[E010](catalog/environment/E010)** | Same Process (scripts) To Deploy To Every Environment. |

---

## Level 4

| **Item**          | **Description** |
| :--                | :--             |
| **[T004](catalog/test/T004)** | Commit Stage Test Coverage > 60%. |
| **[T014](catalog/test/T014)** | Requirement - Acceptance Test Mapping > 20%. |
| **[B006](catalog/build_ci/B006)** | Actively Use Available Analysis Tools (80% sonar-way). |
| **[B007](catalog/build_ci/B007)** | Build Environment Can Be Automatically Created From Version Control. |
| **[B008](catalog/build_ci/B008)** | No manual configuration of CI/CD agent machines. |
| **[E004](catalog/environment/E004)** | Automated Infrastructure Provisioning From Scratch. |
| **[E007](catalog/environment/E007)** | Automated Data Migration While Deploying. |
| **[E005](catalog/environment/E005)** | Automated Infrastructure Upgrade. |
| **[E014](catalog/environment/E014)** | All Transitive Dependency Versions of Direct External Dependencies (related to item E001) Should be Defined. |
| **[D003](catalog/delivery/D003)** | Deployment Frequency Is Once Per Day. |
| **[D007](catalog/delivery/D007)** | Lead Time For Changes Is Less Than One Day. |
| **[D011](catalog/delivery/D011)** | Time To Restore Service Is Less Than One Day. |
| **[D015](catalog/delivery/D015)** | Change Failure Rate Is Less Than 15 Percent. |

---

## Level 5

| **Item**          | **Description** |
| :--               | :--             |
| **[T015](catalog/test/T015)** | Requirement - Acceptance Test Mapping > 50%. |
| **[E008](catalog/environment/E008)** | Data Migration Is Tested. |
| **[D004](catalog/delivery/D004)** | Deployment Frequency Is On-Demand (Multiple Deploy Per Day). |
| **[D008](catalog/delivery/D008)** | Lead Time For Changes Is Less Than One Hour. |
| **[D012](catalog/delivery/D012)** | Time To Restore Service Is Less Than One Hour. |
| **[E009](catalog/environment/E009)** | Ability To Automatic Data Migration Rollback. |
