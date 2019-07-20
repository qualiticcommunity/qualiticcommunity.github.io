# Maturity Levels

Here are the maturity levels. This is what we use as maturity levels and you may change or reorder items in each level.

## Level 1

|**Items**          | **Description** |
|**[T001]({{ site.baseurl }}{% link catalog/test/T001.md%})**| Setup Test Coverage Bundle. |
|**[T005]({{ site.baseurl }}{% link catalog/test/T005.md%})**| Incremental Commit Stage Test Coverage > 10%. |
|**[B001]({{ site.baseurl }}{% link catalog/build_ci/B001.md%})**| All CI/CD scripts are in VC (CI Config in Code). |
|**[T016]({{ site.baseurl }}{% link catalog/test/T016.md%})**| No Release with Red Tests. |

## Level 2

|**Items**          | **Description** |
|**[T006]({{ site.baseurl }}{% link catalog/test/T006.md%})**| Incremental Commit Stage Test Coverage > 50%. |
|**[T002]({{ site.baseurl }}{% link catalog/test/T002.md%})**| Commit Stage Test Coverage > 10%. |
|**[T007]({{ site.baseurl }}{% link catalog/test/T007.md%})**| Classify Tests as Commit, Acceptance, Performance.|
|**[T011]({{ site.baseurl }}{% link catalog/test/T011.md%})**| Acceptance Tests For at Least One Feature Upon Main Use Cases. |
|**[B002]({{ site.baseurl }}{% link catalog/build_ci/B002.md%})**| Automated Code Style Checking. |
|**[B004]({{ site.baseurl }}{% link catalog/build_ci/B004.md%})**| Prevent compiler warning automatically.|
|**[E001]({{ site.baseurl }}{% link catalog/environment/E001.md%})**| All external dependencies for the application are specified in version control and managed with tools/scripts in source control. |
|**[E012]({{ site.baseurl }}{% link catalog/environment/E012.md%})**| Do Not Store Your Secrets in Your Version Control. |
|**[D001]({{ site.baseurl }}{% link catalog/delivery/D001.md%})**|Deployment Frequency is One Per Month. |
|**[D005]({{ site.baseurl }}{% link catalog/delivery/D005.md%})**| Lead Time for Changes is Less Than Six Months.|
|**[D009]({{ site.baseurl }}{% link catalog/delivery/D009.md%})**| Time to Restore Service is Less Than One Month.|
|**[D013]({{ site.baseurl }}{% link catalog/delivery/D013.md%})**| Change Failure Rate Less Than 60 Percent.|

## Level 3

|**Items**          | **Description** |
|**[T003]({{ site.baseurl }}{% link catalog/test/T003.md%})**| Commit Stage Test Coverage > 20%. |
|**[B005]({{ site.baseurl }}{% link catalog/build_ci/B005.md%})**| Actively Use Available Analysis Tools On New Code (50% sonar-way).|
|**[T012]({{ site.baseurl }}{% link catalog/test/T012.md%})**| Acceptance Tests For Each New Feature.|
|**[T013]({{ site.baseurl }}{% link catalog/test/T013.md%})**| Requirement Test Mapping Coverage > 5%. |
|**[E002]({{ site.baseurl }}{% link catalog/environment/E002.md%})**| Automated deployment of the application from scratch. |
|**[E003]({{ site.baseurl }}{% link catalog/environment/E003.md%})**| Automated Upgrade of The Application. |
|**[E013]({{ site.baseurl }}{% link catalog/environment/E013.md%})**| All configuration versioned. |
|**[E006]({{ site.baseurl }}{% link catalog/environment/E006.md%})**| Data Migration Using Versioned Scripts.|
|**[D002]({{ site.baseurl }}{% link catalog/delivery/D002.md%})**| Deployment Frequency is One Per Week. |
|**[D006]({{ site.baseurl }}{% link catalog/delivery/D006.md%})**| Lead Time for Changes is Less Than One Month. |
|**[D010]({{ site.baseurl }}{% link catalog/delivery/D010.md%})**| Time to Restore Service is Less Than One Week. |
|**[D014]({{ site.baseurl }}{% link catalog/delivery/D014.md%})**| Change Failure Rate Less Than 45 Percent. |
