# software-composition-analysis-SCA-tool.
Its main purpose is to help developers manage and reduce security and licensing risks associated with open source and third-party components used in their software applications. Therefore, it can be classified under the category of software development tools, specifically SCA tools.
### About Code Insight Scans
A Code Insight scan processes codebase files to identify evidence of OSS and third-party code. The scan results are then processed by Code Insight, which creates inventory of the detected OSS and third-party components, detects licenses and security vulnerabilities, applies policies for automated review, and creates review and remediation tasks per project configuration.

The following describes the types of Code Insight scans and the analysis techniques used by scans:

## Scan Types
Code Insight scans typically fall into three categories:

## Code repository scans:
These scans analyze code stored in a version control system such as Git, SVN or Perforce.

## Binary repository scans: 
These scans analyze binaries stored in a binary repository such as JFrog Artifactory or Nexus Repository Manager.

## Package manager scans: 
These scans analyze package manifests for popular package managers such as npm, Maven, or RubyGems.

# Scan Analysis Techniques
Code Insight scans use a variety of analysis techniques to identify OSS and third-party components, licenses, and security vulnerabilities. These techniques include:

## Signature scanning:
This technique uses checksums or hashes to match code against known software components.

## Fingerprinting: 
This technique uses algorithms to compare code against a database of known components and identify similarities.

## Package analysis: 
This technique examines package manifests to identify dependencies and their associated licenses and vulnerabilities.

## Machine learning: 
This technique uses algorithms to analyze code and identify patterns and characteristics of known software components.

## Binary analysis: 
This technique decompiles binaries and analyzes the resulting code to identify known components and vulnerabilities.


# Scan Profiles
Code Insight scans can be configured using scan profiles, which specify the types of scans to perform, the analysis techniques to use, and the policies to enforce. Profiles can be customized for different projects or departments within an organization, depending on the specific needs and requirements of each team. Profiles can also be scheduled to run on a regular basis to ensure ongoing monitoring of OSS and third-party components used in codebases.
