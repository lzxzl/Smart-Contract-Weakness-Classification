# 缩略语

- SWC：**Smart Contract Weakness Classification** （大概是原仓库作者定义的）
- SCSVS：[Smart Contract Security Verification Standard](https://github.com/ComposableSecurity/SCSVS),

# Please note, this content is no longer actively maintained.

The content of the SWC registry has not been thoroughly updated since 2020. It is known to be incomplete and may contain errors as well as crucial omissions.

For currently maintained guidance on known Smart Contract vulnerabilities written primarily as guidance for security reviewers, please see the
[EEA EthTrust Security Levels specification](https://entethalliance.org/specs/ethtrust-sl). As well as the latest release version, an
[Editor's draft](https://entethalliance.github.io/eta-registry/security-levels-spec.html) is available, 
that represents the latest work of the group developing the specification.

General guidance for developers on how to ensure security, that is currently maintained, is also available through the 
[Smart Contract Security Verification Standard (SCSVS)](https://github.com/ComposableSecurity/SCSVS), or
the [Smart Contract Security Field Guide](https://scsfg.io).

The following table contains an overview of the SWC registry. Each row consists of an SWC identifier (ID), weakness title, CWE parent and list of related code samples. The links in the ID and Test Cases columns link to the respective SWC definition. Links in the Relationships column link to the CWE Base or Class type.

| ID                           | Title                                                   | Relationships                                                |
| ---------------------------- | ------------------------------------------------------- | ------------------------------------------------------------ |
| [SWC-136](./docs/SWC-136.md) | Unencrypted Private Data On-Chain                       | [CWE-767: Access to Critical Private Variable via Public Method](https://cwe.mitre.org/data/definitions/767.html) |
| [SWC-135](./docs/SWC-135.md) | Code With No Effects                                    | [CWE-1164: Irrelevant Code](https://cwe.mitre.org/data/definitions/1164.html) |
| [SWC-134](./docs/SWC-134.md) | Message call with hardcoded gas amount                  | [CWE-655: Improper Initialization](https://cwe.mitre.org/data/definitions/665.html) |
| [SWC-133](./docs/SWC-133.md) | Hash Collisions With Multiple Variable Length Arguments | [CWE-294: Authentication Bypass by Capture-replay](https://cwe.mitre.org/data/definitions/294.html) |
| [SWC-132](./docs/SWC-132.md) | Unexpected Ether balance                                | [CWE-667: Improper Locking](https://cwe.mitre.org/data/definitions/667.html) |
| [SWC-131](./docs/SWC-131.md) | Presence of unused variables                            | [CWE-1164: Irrelevant Code](https://cwe.mitre.org/data/definitions/1164.html) |
| [SWC-130](./docs/SWC-130.md) | Right-To-Left-Override control character (U+202E)       | [CWE-451: User Interface (UI) Misrepresentation of Critical Information](http://cwe.mitre.org/data/definitions/451.html) |
| [SWC-129](./docs/SWC-129.md) | Typographical Error                                     | [CWE-480: Use of Incorrect Operator](https://cwe.mitre.org/data/definitions/480.html) |
| [SWC-128](./docs/SWC-128.md) | DoS With Block Gas Limit                                | [CWE-400: Uncontrolled Resource Consumption](https://cwe.mitre.org/data/definitions/400.html) |
| [SWC-127](./docs/SWC-127.md) | Arbitrary Jump with Function Type Variable              | [CWE-695: Use of Low-Level Functionality](https://cwe.mitre.org/data/definitions/695.html) |
| [SWC-126](./docs/SWC-126.md) | Insufficient Gas Griefing                               | [CWE-691: Insufficient Control Flow Management](https://cwe.mitre.org/data/definitions/691.html) |
| [SWC-125](./docs/SWC-125.md) | Incorrect Inheritance Order                             | [CWE-696: Incorrect Behavior Order](https://cwe.mitre.org/data/definitions/696.html) |
| [SWC-124](./docs/SWC-124.md) | Write to Arbitrary Storage Location                     | [CWE-123: Write-what-where Condition](https://cwe.mitre.org/data/definitions/123.html) |
| [SWC-123](./docs/SWC-123.md) | Requirement Violation                                   | [CWE-573: Improper Following of Specification by Caller](https://cwe.mitre.org/data/definitions/573.html) |
| [SWC-122](./docs/SWC-122.md) | Lack of Proper Signature Verification                   | [CWE-345: Insufficient Verification of Data Authenticity](https://cwe.mitre.org/data/definitions/345.html) |
| [SWC-121](./docs/SWC-121.md) | Missing Protection against Signature Replay Attacks     | [CWE-347: Improper Verification of Cryptographic Signature](https://cwe.mitre.org/data/definitions/347.html) |
| [SWC-120](./docs/SWC-120.md) | Weak Sources of Randomness from Chain Attributes        | [CWE-330: Use of Insufficiently Random Values](https://cwe.mitre.org/data/definitions/330.html) |
| [SWC-119](./docs/SWC-119.md) | Shadowing State Variables                               | [CWE-710: Improper Adherence to Coding Standards](http://cwe.mitre.org/data/definitions/710.html) |
| [SWC-118](./docs/SWC-118.md) | Incorrect Constructor Name                              | [CWE-665: Improper Initialization](http://cwe.mitre.org/data/definitions/665.html) |
| [SWC-117](./docs/SWC-117.md) | Signature Malleability                                  | [CWE-347: Improper Verification of Cryptographic Signature](https://cwe.mitre.org/data/definitions/347.html) |
| [SWC-116](./docs/SWC-116.md) | Block values as a proxy for time                        | [CWE-829: Inclusion of Functionality from Untrusted Control Sphere](https://cwe.mitre.org/data/definitions/829.html) |
| [SWC-115](./docs/SWC-115.md) | Authorization through tx.origin                         | [CWE-477: Use of Obsolete Function](https://cwe.mitre.org/data/definitions/477.html) |
| [SWC-114](./docs/SWC-114.md) | Transaction Order Dependence                            | [CWE-362: Concurrent Execution using Shared Resource with Improper Synchronization ('Race Condition')](https://cwe.mitre.org/data/definitions/362.html) |
| [SWC-113](./docs/SWC-113.md) | DoS with Failed Call                                    | [CWE-703: Improper Check or Handling of Exceptional Conditions](https://cwe.mitre.org/data/definitions/703.html) |
| [SWC-112](./docs/SWC-112.md) | Delegatecall to Untrusted Callee                        | [CWE-829: Inclusion of Functionality from Untrusted Control Sphere](https://cwe.mitre.org/data/definitions/829.html) |
| [SWC-111](./docs/SWC-111.md) | Use of Deprecated Solidity Functions                    | [CWE-477: Use of Obsolete Function](https://cwe.mitre.org/data/definitions/477.html) |
| [SWC-110](./docs/SWC-110.md) | Assert Violation                                        | [CWE-670: Always-Incorrect Control Flow Implementation](https://cwe.mitre.org/data/definitions/670.html) |
| [SWC-109](./docs/SWC-109.md) | Uninitialized Storage Pointer                           | [CWE-824: Access of Uninitialized Pointer](https://cwe.mitre.org/data/definitions/824.html) |
| [SWC-108](./docs/SWC-108.md) | State Variable Default Visibility                       | [CWE-710: Improper Adherence to Coding Standards](https://cwe.mitre.org/data/definitions/710.html) |
| [SWC-107](./docs/SWC-107.md) | Reentrancy                                              | [CWE-841: Improper Enforcement of Behavioral Workflow](https://cwe.mitre.org/data/definitions/841.html) |
| [SWC-106](./docs/SWC-106.md) | Unprotected SELFDESTRUCT Instruction                    | [CWE-284: Improper Access Control](https://cwe.mitre.org/data/definitions/284.html) |
| [SWC-105](./docs/SWC-105.md) | Unprotected Ether Withdrawal                            | [CWE-284: Improper Access Control](https://cwe.mitre.org/data/definitions/284.html) |
| [SWC-104](./docs/SWC-104.md) | Unchecked Call Return Value                             | [CWE-252: Unchecked Return Value](https://cwe.mitre.org/data/definitions/252.html) |
| [SWC-103](./docs/SWC-103.md) | Floating Pragma                                         | [CWE-664: Improper Control of a Resource Through its Lifetime](https://cwe.mitre.org/data/definitions/664.html) |
| [SWC-102](./docs/SWC-102.md) | Outdated Compiler Version                               | [CWE-937: Using Components with Known Vulnerabilities](http://cwe.mitre.org/data/definitions/937.html) |
| [SWC-101](./docs/SWC-101.md) | Integer Overflow and Underflow                          | [CWE-682: Incorrect Calculation](https://cwe.mitre.org/data/definitions/682.html) |
| [SWC-100](./docs/SWC-100.md) | Function Default Visibility                             | [CWE-710: Improper Adherence to Coding Standards](https://cwe.mitre.org/data/definitions/710.html) |
