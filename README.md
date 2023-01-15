# Security Audit for the BNBNodes Smart Contract

<img src="web3audits.png" width="300" />

*Approved by Web3Audits DMCC*

## Details of this engagement
- Platform: BNB Chain
- Language: Solidity
- Methods: Architecture Review, Functional Testing, Computer-Aided Verification, Manual Review
- Repository: 
    - Commit: 8cdf2cf7c30ab3907dc899131adbeecd13b8de63
    - Documentation: [YES](https://docs.bnbnodes.io)
    - Files in Scope: [BNBNodes.sol](https://github.com/bnbnodes/contract/blob/main/BNBNodes.sol) 
    - Tests: [YES], 98% Coverage
- Website: [bnbnodes.io](https://bnbnodes.io)
- Timeline: January 01 - January 11, 2023
- Changelog: 
    - Initial Audit on January 5th
    - Remediated Audit

## Introduction
Web3Audits (Auditor) was contracted by BNBNodes (Customer) to conduct a Smart Contract Code Review and Security Analysis. This report presents the findings of the security assessment of the Customer's smart contract and its code review conducted between January 1st, 2023 - January 5th, 2023. The second review was provided on January 11th , 2023.

## Executive Summary
According to the assessment, the Customer's smart contracts are well-secured.
Web3Audits performed an analysis of code functionality, manual audit, and automated checks with Mythril and Slither. All issues found during automated analysis were manually reviewed.

- **As a result of the audit, security engineers found no severity issues.**
- **As a result of the second audit, security engineers found no severity issues.**

## Audit overview

Risk Level | Issues  
---|---
Critical | **No critical issues were found.**
High | **No high severity issues were found.**
Medium | **No medium severity issues were found.**
Low  | **No low severity issues were found.**


## Conclusion
Smart contracts within the scope were manually reviewed and analyzed with static analysis tools.
The audit report contains all found security vulnerabilities and other issues in the reviewed code.
- **As a result of the audit, security engineers found no severity issues.**
- **As a result of the second audit, security engineers found no severity issues.**

### Severity Definitions

Risk Level | Description  
---|---
*Critical* | Critical vulnerabilities are usually straightforward to exploit and can lead to assets loss or data manipulations.
*High* | High vulnerabilities are difficult to exploit; however, they also have a significant impact on smart contract execution, e.g., public access to crucial functions
*Medium* | Medium-level vulnerabilities are important to fix; however, they can't lead to assets loss or data manipulations.
*Low* |  Low vulnerabilities are mostly related to outdated, unused, etc. code snippets that can't have a significant impact on execution

### Disclaimer

- Web3Audits analyzed the smart contracts in scope in accordance with the best industry practices at the date of this report, in relation to cybersecurity vulnerabilities and issues in smart contract source code, the details of which are disclosed in this report (Source Code); the Source Code compilation, deployment, and functionality (performing the intended functions).
- Web3Audits makes no statements or warranties on the security of the code. It also cannot be considered as a sufficient assessment regarding the utility and safety of the code, bug-free status, or any other statements of the contract. While we have done our best in conducting the analysis and producing this report, it is important to note that you should not rely on this report only — we recommend proceeding with several independent audits and a public bug bounty program to ensure the security of smart contracts.
- Web3Audits notes that smart contracts are deployed and executed on a blockchain platform. The platform, its programming language, and other software related to the smart contract can have vulnerabilities that can lead to hacks. Thus, the audit can not guarantee the explicit security of the audited smart contracts.

### Notice
This document may contain confidential information about IT systems and the intellectual property of the Customer as well as
information about potential vulnerabilities and methods of their exploitation. The report containing confidential information can be used internally by the Customer, or it can be disclosed publicly after all vulnerabilities are fixed — upon a decision of the Customer.
