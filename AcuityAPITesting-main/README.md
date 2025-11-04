# Acuity API Testing

This repository is designed to facilitate the testing and validation of Acuity platform APIs and related cloud workflows. It contains a variety of Postman collections, sample payloads, and workflow definitions for different business processes and integration scenarios.

## Repository Objective

The primary objective of this repository is to serve as a central hub for automated and manual testing resources targeting Acuity APIs and their integrations with AWS and other ecosystem components. It is intended for use by QA engineers, developers, and DevOps teams to ensure the reliability and accuracy of workflows across environments.

## Collections and Structure

The repository includes the following key directories and collections:

- **AMP and Appscope**  
  Contains resources and test collections related to AMP and Appscope integrations.

- **AWS SNS Publish and S3 Events**  
  Test data and workflow definitions for scenarios involving AWS SNS notifications and S3 event triggers.

- **AcuityCMP_DigitalOrderCreation_WF_TEST**  
  Workflow test data for AcuityCMP digital order creation processes.

- **Acuity_OrderCreation_AWS_WF**  
  Payloads and test cases for Acuity order creation using AWS workflow integrations.

- **CMP Acuity_Order Hybrid Creation TEST**  
  Resources for hybrid order creation process testing within the CMP platform.

- **CMP Acuity_OrderCreation UAT**  
  UAT (User Acceptance Testing) payloads and workflow scenarios for CMP Acuity order creation.

- **CMP Digital_Orders_Creation TEST**  
  Postman collections and payloads for digital order creation testing in CMP.


- **CMP Digital_Orders_Creation UAT DataCollector_SH**  
  UAT test scenarios focusing on DataCollector_SH flows in digital order creation.

- **CMP Digital_Orders_Creation UAT**  
  User acceptance test resources for digital orders creation in CMP.

- **Class INvision - CI**  
  Continuous integration test cases and data for the INvision class workflows.

- **CMP Acuity_OrderCreation TEST**  
  Central directory for Postman collections that drive API and workflow testing. Use these collections to automate and document API tests across the above business scenarios.

- **cv_propertydata v2**  
  Postman collection focused on testing the latest property data APIs within the Acuity platform. Includes validation workflows, edge case scenarios, and integration tests covering property data retrieval, updates, and synchronization across supported environments.

## Usage

1. Clone this repository.
2. Import relevant Postman collections from `postman/collections` into your Postman workspace.
3. Use sample payloads and workflow definitions from the appropriate directories to run or automate tests.

## Contribution

Please create a new branch for your changes. Once your branch is ready, submit a Pull Request (PR) for review. Merging to protected branches is only allowed after meeting the acceptance criteria and required approvals.

---

For questions or feedback, please contact the repository maintainers.
