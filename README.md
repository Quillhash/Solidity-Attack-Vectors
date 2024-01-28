# Solidity Smart Contract Attack Vectors:

This Repository contains list of Solidity Attack Vectors. It includes most solidity vulnerabilities collected from various sources like SWC Registry, DeFi threat, DASP Top-10 and contents all over Internet. You can click each attack vectors and find details about it. This repository will be actively maintained and updated by QuillAudits.

#### If you find any attack vectors missing, you can create a pull request and be a contributor of the project.

![](/mindmaps/Solidity_Vectors_QuillAudits.png)



---
Serial No. | Attack Vectors
--- | ---
**1** | [Access Control Checks on Critical Function](data/1.md)
**2** | [Account Existence Check for low level calls](data/2.md)
**3** | [Arithmetic Over/Under Flows](data/3.md)
**4** | [Assert Violation](data/4.md)
**5** | [Authorization through tx.origin](data/5.md)
**6** | [Bad Source of Randomness](data/6.md)
**7** | [Block Timestamp manipulation](data/7.md)
**8** | [Bypass Contract Size Check](data/8.md)
**9** | [Code With No Effects](data/9.md)
**10** | [Delegatecall](data/10.md)
**11** | [Delegatecall to Untrusted Callee](data/11.md)
**12** | [DoS with (Unexpected) revert](data/12.md)
**13** | [DoS with Block Gas Limit](data/13.md)
**14** | [Logical Issues](data/14.md)
**15** | [Entropy Illusion](data/15.md)
**16** | [Function Selector Abuse](data/16.md)
**17** | [Floating Point and Numerical Precision](data/17.md)
**18** | [Floating Pragma](data/18.md)
**19** | [Forcibly Sending Ether to a Contract](data/19.md)
**20** | [Function Default Visibility](data/20.md)
**21** | [Hash Collisions With Multiple Variable Length Arguments](data/21.md)
**22** | [Improper Array Deletion](data/22.md)
**23** | [Incorrect interface](data/23.md)
**24** | [Insufficient gas griefing](data/24.md)
**25** | [Unsafe Ownership Transfer](data/25.md)
**26** | [Loop through long arrays](data/26.md)
**27** | [Message call with hardcoded gas amount](data/27.md)
**28** | [Outdated Compiler Version](data/28.md)
**29** | [Precision Loss in Calculations](data/29.md)
**30** | [Price Manipulation](data/30.md)
**31** | [Hiding Malicious Code with External Contract](data/31.md)
**32** | [Public burn() function](data/32.md)
**33** | [Race Conditions / Front Running](data/33.md)
**34** | [Re-entrancy](data/34.md)
**35** | [Requirement Violation](data/35.md)
**36** | [Right-To-Left-Override control character (U+202E)](data/36.md)
**37** | [Shadowing State Variables](data/37.md)
**38** | [Short Address/Parameter Attack](data/38.md)
**39** | [Signature Malleability](data/39.md)
**40** | [Signature Replay Attacks](data/40.md)
**41** | [State Variable Default Visibility](data/41.md)
**42** | [Transaction Order Dependence](data/42.md)
**43** | [Typographical Error](data/43.md)
**44** | [Unchecked Call Return Value](data/44.md)
**45** | [Unencrypted Private Data On-Chain](data/45.md)
**46** | [Unexpected Ether balance](data/46.md)
**47** | [Uninitialized Storage Pointer](data/47.md)
**48** | [Unprotected Ether Withdrawal](data/48.md)
**49** | [Unprotected SELFDESTRUCT Instruction](data/49.md)
**50** | [Unprotected Upgrades](data/50.md)
**51** | [Unused Variable](data/51.md)
**52** | [Use of Deprecated Solidity Functions](data/52.md)
**53** | [Write to Arbitrary Storage Location](data/53.md)
**54** | [Wrong inheritance](data/54.md)
------
## References:

[SWC Registry](https://swcregistry.io/)

[DeFi-Threat](https://github.com/manifoldfinance/defi-threat)

[Runtimeverification - List-of-Security-Vulnerabilties](https://github.com/runtimeverification/verified-smart-contracts/wiki/List-of-Security-Vulnerabilities)

[DASP-Top 10](https://www.dasp.co/)
