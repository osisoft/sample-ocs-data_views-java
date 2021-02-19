# Using OCS Data Views in Java

**Version:** 1.0.5

[![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/osisoft.sample-ocs-data_views-java?repoName=osisoft%2Fsample-ocs-data_views-java&branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=2617&repoName=osisoft%2Fsample-ocs-data_views-java&branchName=master)

The sample code in this demonstrates how to invoke Data View REST APIs via the sample Java client [library](https://github.com/osisoft/sample-ocs-sample_libraries-java). The sample demonstrates how to establish a connection to SDS, obtain an authorization token, create an SdsType and SdsStream with data (if needed), create a data view, update it, retrieve it, and retrieve data from it in different ways. At the end of the sample, everything that was created is deleted.

## Summary of steps to run the Java demo

1. Clone a local copy of this GitHub repository.
1. Install the [Java Client Library](https://github.com/osisoft/sample-ocs-sample_libraries-java) (see its [readme](https://github.com/osisoft/sample-ocs-sample_libraries-java) for instructions)
1. The sample is configured using the file [config.placeholder.properties](config.placeholder.properties). Before editing, rename this file to `config.properties`.
   - This repository's `.gitignore` rules should prevent the file from ever being checked in to any fork or branch, to ensure credentials are not compromised.
1. Replace the configuration strings in `config.properties`
1. Build and run the project.
   1. `cd` to your project location.
   1. run `mvn package exec:java` on cmd.

\*Currently this project is not hosted on the central Maven repo and must be compiled and installed locally.

---

Tested against Maven 3.6.3 and Java Runtime Environment 11.

For the main OCS data view samples page on master [ReadMe](https://github.com/osisoft/OSI-Samples-OCS/blob/master/docs/DATA_VIEWS_README.md)  
For the main OCS samples page on master [ReadMe](https://github.com/osisoft/OSI-Samples-OCS)  
For the main OSIsoft samples page on master [ReadMe](https://github.com/osisoft/OSI-Samples)
