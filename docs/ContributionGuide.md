# Contribution Guide for Log Samples Repository

## Introduction

This guide provides detailed instructions on how to contribute log samples and their corresponding parser definitions to the Log Samples Repository. Our goal is to build a comprehensive, anonymized archive of log data that can be used for a wide range of purposes, from software development to cybersecurity analysis.

## Preparing Your Log Sample

1. **Anonymize Your Log Data:** Ensure that all sensitive information is removed or obfuscated. This includes IP addresses, usernames, passwords, and any other personally identifiable information (PII).

2. **Structure Your Submission:** Each log sample should be placed in its own folder, structured as follows:
    - `raw/`: Contains the sample log files.
    - `definition/`: Contains a JSON file with the parsing definitions.

## Creating Parser Definitions

1. **Define Your Parser:** Refer to the provided JSON structure for creating a parser definition. This includes specifying the vendor, product name, version, and the parsing expressions.

2. **Choose Your Parsing Method:** Decide whether your log sample will be parsed using delimiters or regular expressions, and provide the necessary details in your JSON definition.

## Submitting Your Contribution

1. **Fork the Repository:** Start by forking the repository to your GitHub account.

2. **Add Your Log Sample and Parser Definition:** Follow the repository structure to add your log sample and parser definition to your fork.

3. **Create a Pull Request:** Once you've added your contribution, submit a pull request to the main repository for review.

## Guidelines for Contribution

- Make sure your log samples are properly anonymized.
- Follow the structured format for parser definitions to ensure consistency.
- Provide clear and concise documentation for your log samples and parser definitions.

Thank you for contributing to the Log Samples Repository! Your contributions help the community by providing valuable resources for research and development.
