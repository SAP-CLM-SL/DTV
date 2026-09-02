# CLM Day 2026 - Data Transition Validation

## Overview

This hands-on session introduces **Data Transition Validation (DTV)** and provides a practical walkthrough for validating data during a transition from an **SAP ECC source system** to an **SAP S/4HANA target system**.

During the exercise, you will create a DTV project, maintain the source and target systems, import pre-delivered validation content, configure test specifications, run simulations, execute data extraction, evaluate the extracted data, and validate the results.

You will also work with a custom validation report and learn how to analyze and mitigate discrepancies identified by DTV.

## Required Systems & Services

- [x] **SAP ECC Source System** — Source system used to create and configure the DTV project and perform source data extraction.
- [x] **SAP S/4HANA Target System** — Target system used to execute target-side data extraction and validation.
- [x] **Data Transition Validation (DTV)** — Tool used to configure, extract, evaluate, and validate data between the source and target systems.

## Exercise Navigation

Follow the exercises in sequence:

1. [Exercise 1 - Login to ECC Source System](ex1/README.md)
2. [Exercise 2 - Create DTV Project](ex2/README.md)
3. [Exercise 3 - Maintain System](ex3/README.md)
4. [Exercise 4 - Import the Pre-delivered Content and perform Import Specification](ex4/README.md)
5. [Exercise 5 - Define Test specification for the selected Reports](ex5/README.md)
6. [Exercise 5.1 - Maintain Project Global Data](ex5-1/README.md)
7. [Exercise 5.2 - Complete the test specification for RFITEMGL](ex5-2/README.md)
8. [Exercise 5.3 - Complete the test specification for RM07MMFI](ex5-3/README.md)
9. [Exercise 5.4 - Complete the test specification for RFBELJ00](ex5-4/README.md)
10. [Exercise 6 - Run Simulation](ex6/README.md)
11. [Exercise 7 - Add Custom report and Configure Test Specification](ex7/README.md)
12. [Exercise 8 - Execute Data Extraction for the source system](ex8/README.md)
13. [Exercise 9 - Login to the S/4HANA system and Execute Extraction](ex9/README.md)
14. [Exercise 10 - Run Evaluation](ex10/README.md)
15. [Exercise 11 - Validate Results](ex11/README.md)
16. [Exercise 12.1 - Mitigating RM07MMFI issue](ex12-1/README.md)
17. [Exercise 12.2 - Mitigating the custom report issue](ex12-2/README.md)


## Expected Outcome

At the end of this hands-on, you should be able to:

- Navigate to the DTV tool in an SAP ECC system.
- Create and configure a DTV project.
- Maintain source and target system information.
- Import pre-delivered validation content.
- Maintain project global data.
- Configure report test specifications.
- Add a custom report and configure its variant.
- Generate work items and run simulations.
- Execute data extraction in both source and target systems.
- Run evaluations for the extracted reports and tables.
- Analyze DTV validation results.
- Identify differences, missing data, and unexpected target data.
- Investigate discrepancies and apply appropriate mitigation.

## Resources

Refer to the SAP DTV documentation available for further information.

## Code of Conduct

Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License

Copyright (c) 2026 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
