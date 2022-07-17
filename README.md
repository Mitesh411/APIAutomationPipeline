
[![Test-Build](https://github.com/Mitesh411/APIAutomationPipeline/actions/workflows/mayhem-for-api.yml/badge.svg?branch=main)](https://github.com/Mitesh411/APIAutomationPipeline/actions/workflows/mayhem-for-api.yml)

<img src ="https://logos-download.com/wp-content/uploads/2020/06/Postman_Logo-700x259.png">

# APIAutomationPipeline
API Automation in Github Action Pipeline Demo
YAML File Added 

# POSTMAN-REPORTS
This repo shows how to run `postman collection` using `newman` within the `GitHub Actions` job and generate `htmlextra` test results report

## Steps
1. Download and Install [Postman](https://www.postman.com/downloads/)
2. Create a new `Collection` and save your requests in a collection for reuse and sharing
3. Create a new `Environment` and save values you frequently use in an environment
4. Export the newly created `Collection` along with the `Environment` from `Postman` to your local directory
5. Add the `postman_collection` and `postman_environment` to newly created `GitHub` repository
6. Create an `GitHub Actions` workflow ( i.e., `.github/workflows/github-actions-htmlextra-report.yml` ) to run `postman collection` using `newman` and generate `test report` via `html extra reporter`
7. Upon every `push` and `pull_request`, the workflow would be triggered with `Artifacts` produced during runtime ( i.e., `test-run-reports` ) which contains the html report ( i.e., `test_report.html` )
